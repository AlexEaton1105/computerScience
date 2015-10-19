```
START

INPUT name
INPUT userclass

IF userClass = 1:
  OPEN classOne.txt;
ELIF userCLass = 2:
  OPEN classTwo.txt;
ELSE:
  OPEN classThree.txt;
  
COMPLETE arithmeticQuiz

WRITE name AND score to class file
CLOSE class file

END
```
