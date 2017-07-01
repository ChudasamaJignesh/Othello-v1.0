## FILE STRUCTURE OF PROJECT <br />


C:\Users\Jignesh\Documents\NetBeansProjects\Othello1.0>tree /F
Folder PATH listing
Volume serial number is 000000FA AA24:668C
C:.
│   build.xml
│   manifest.mf
│
├───dist
│       Othello1.0.jar
│       README.TXT
│
├───images
│       black_disk.png
│       white_disk.png
│
├───nbproject
│   │   build-impl.xml
│   │   genfiles.properties
│   │   project.properties
│   │   project.xml
│   │
│   └───private
│           config.properties
│           private.properties
│           private.xml
│
├───src
│   │   tests.rar
│   │
│   ├───listeners
│   │       ForfeitListener.java
│   │       NewGameListener.java
│   │       PlaceDiskListener.java
│   │       RedoListener.java
│   │       UndoListener.java
│   │
│   ├───main_components
│   │       Board.java
│   │       Button.java
│   │       Color.java
│   │       Command.java
│   │       CommandManager.java
│   │       Controller.java
│   │       Disk.java
│   │       GameLoop.java
│   │       Player.java
│   │       View.java
│   │
│   └───strategies
│           AlphaBetaStrategy.java
│           BoardComparatorWhite.java
│           Difficulty.java
│           MinimaxStrategy.java
│           RandomStrategy.java
│           ScoreComparatorWhite.java
│           Strategy.java
│           Utility.java
│
└───test
