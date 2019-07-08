# Android-Material-Stepper-Example
This application allows to use Material steppers inside Android applications.
Add below line to your app level build.gradle and sync project
implementation 'com.stepstone.stepper:material-stepper:3.2.3'

Butterknief - 
implementation 'com.jakewharton:butterknife:10.0.0'
annotationProcessor 'com.jakewharton:butterknife-compiler:10.0.0'

for design of stepper, add below lines to your xml file

  <com.stepstone.stepper.StepperLayout
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:id="@+id/stepperLayout"
        app:ms_stepperType="dots">
    </com.stepstone.stepper.StepperLayout>

You can change stepper type as - tabs, progress_bar, dots

Thanks for download.
Suggest something which you want from me, your suggestion are always welcome :)
