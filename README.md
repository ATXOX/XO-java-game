# XO-java-game


Follow the below steps to enable JavaFX with VS code:

1) Download JavaFX zip folder from this website: https://gluonhq.com/products/javafx/
2) Extract the zip folder. You will notice that you will extract javafx-sdk-19 folder. Inside
this folder, there is another folder that called lib, which you will need soon.
3) Now, Open VS code and createa new Java project
4) In the src folder of your project, copy/paste one the JavaFX programs that you can find
on Mycourses. For example, copy/paste MyJavaFX.java
5) You will notice that you will get many syntax errors. To fix them do the following.
6) Hover over Referenced Libraries and click +, then add all files inside javafx-sdk-19/lib
7) Use File → Preferences → Settings to open User Settings.
Search for "vmargs" and you should see Java > Debug > Settings: Vm Args in the filtered
list.
Type or paste the text below into the field, but replace <Your JavaFX lib> with the full
path to the javafx-sdk-11.0.02/lib folder on your computer.
--module-path <Your JavaFX lib> --add-modules javafx.controls,javafx.fxml
8) The syntax errors will not disappear and you can now run your javafx class.
