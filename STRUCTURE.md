## FILE STRUCTURE OF PROJECT <br />

C:.<br />
│   build.xml<br />
│   manifest.mf<br />
│<br />
├───images<br />
│       black_disk.png<br />
│       white_disk.png<br />
│<br />
├───nbproject<br />
│   │   build-impl.xml<br />
│   │   genfiles.properties<br />
│   │   project.properties<br />
│   │   project.xml<br />
│   │<br />
│   └───private<br />
│           config.properties<br />
│           private.properties<br />
│           private.xml<br />
│<br />
├───src<br />
│   │   tests.rar<br />
│   │<br />
│   ├───listeners<br />
│   │       ForfeitListener.java<br />
│   │       NewGameListener.java<br />
│   │       PlaceDiskListener.java<br />
│   │       RedoListener.java<br />
│   │       UndoListener.java<br />
│   │<br />
│   ├───main_components<br />
│   │       Board.java<br />
│   │       Button.java<br />
│   │       Color.java<br />
│   │       Command.java<br />
│   │       CommandManager.java<br />
│   │       Controller.java<br />
│   │       Disk.java<br />
│   │       GameLoop.java<br />
│   │       Player.java<br />
│   │       View.java<br />
│   │<br />
│   └───strategies<br />
│           AlphaBetaStrategy.java<br />
│           BoardComparatorWhite.java<br />
│           Difficulty.java<br />
│           MinimaxStrategy.java<br />
│           RandomStrategy.java<br />
│           ScoreComparatorWhite.java<br />
│           Strategy.java<br />
│           Utility.java<br />
│<br />
└───test<br />
