* interpreter
  
  ```bash
  #!/bin/bash
  ```

* if statement

  ```bash
  if [ $l -le 2 ]
  then
    # do something
  fi
  ```

* read each line from file
  (not necessary in most cases, use `awk` instead)

  ```bash
  cat $FILE | while read LINE
  do
    # do something
  done
  ```  

* get line number

  ```bash
  m=`wc -l $FILE | awk '{print $1}'`
  ```
  
* get word count per line

  ```bash
  awk '{ print NF}' < $FILE > word_count
  ```
  
* filter lines in file

  ```bash
  awk 'NF<=2 {print $0}' $FILE
  ```
  
* get vocabulary of the file

  ```bash
  tr ' ' '\n' < $FILE | sort | uniq
  ```
  
* remove first two word per line

  ```bash
  cut -d' ' -f3- $FILE
  ```
