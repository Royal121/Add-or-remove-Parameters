package com.example.android.myapplication;

import androidx.appcompat.app.AppCompatActivity;

import android.os.Bundle;

public class MainActivity extends AppCompatActivity {

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);
         messagesent(2020,"Delhi", "12:00 AM");





    }


    public String messagesent(int messagesent,String city,String time){
      return  "Happy New Year" + messagesent + city + time;
    }


}
