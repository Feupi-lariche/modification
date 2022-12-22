# modification
activity_main.xml
<?xml version="1.0" encoding="utf-8"?>
   <LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
        xmlns:app="http://schemas.android.com/apk/res-auto"
        xmlns:tools="http://schemas.android.com/tools"
        android:layout_width="match_parent"
       android:layout_height="match_parent"
        android:orientation="vertical"
       android:layout_gravity="center"
        android:gravity="center"
       android:padding="18dp"
       tools:context=".MainActivity">
   
       <TextView
           android:layout_width="match_parent"
           android:layout_height="wrap_content"
           android:text="Login Form"
           android:textColor="@color/colorPrimary"
           android:textSize="20sp"
           android:textStyle="bold"
           android:gravity="center"/>
   
   
   
       <com.google.android.material.textfield.TextInputLayout
           android:id="@+id/text_input_email"
           android:layout_width="match_parent"
           android:layout_height="wrap_content"
           app:errorEnabled="true"
           android:layout_marginTop="50dp">
   
           <com.google.android.material.textfield.TextInputEditText
               android:layout_width="match_parent"
               android:layout_height="wrap_content"
               android:hint="Email"
               android:inputType="textEmailAddress" />
   
       </com.google.android.material.textfield.TextInputLayout>
   
       <com.google.android.material.textfield.TextInputLayout
           android:id="@+id/text_input_password"
           android:layout_width="match_parent"
           android:layout_height="wrap_content"
           android:layout_marginTop="11dp"
           app:errorEnabled="true"
           app:passwordToggleEnabled="true">
  
          <com.google.android.material.textfield.TextInputEditText
               android:layout_width="match_parent"
               android:layout_height="wrap_content"
              android:hint="Password"
               android:inputType="textPassword" />
   
       </com.google.android.material.textfield.TextInputLayout>
   
       <Button
           android:layout_width="match_parent"
           android:layout_height="wrap_content"
           android:onClick="confirmInput"
           android:text="Confirm"
           android:textColor="@color/colorWhite"
           android:layout_marginTop="22dp"
           android:background="@color/colorPrimary"/>
   
   </LinearLayout>
