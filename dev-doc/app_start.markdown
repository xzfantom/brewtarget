Application start
=================

Short overview of the way the application starts.

# main.cpp

    Set some QT properties for QTApplication
    Check if no other instance of BT is running
    If command line parameters found, executes them and exits
    Goes to Brewtarget::run

# brewtarget.cpp

    