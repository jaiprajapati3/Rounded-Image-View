This tutorial shows you how to create rouded image view in android.

 Add roundedimageview-debug.aar in your project.4
 
 Project > New > Module >Import JAR/.AAR Package > Select roundedimageview-debug.aar
 
 Open build.gradle and add dependency.
 
dependencies {
    compile project(":roundedimageview-debug")
}

In layout.xml file add below code.


   <androidpugnator.roundedimageview.RoundImageView
   
        android:layout_width="100dp"
        
        android:layout_height="100dp"
        
        android:src="@drawable/yourimage"
        
        android:layout_centerHorizontal="true"
        
        android:layout_centerVertical="true"/>
