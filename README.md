# ANDROID
package com.example.sjcet.listview;

import android.content.ClipData;
import android.support.v7.app.AppCompatActivity;
import android.os.Bundle;
import android.view.View;
import android.widget.Adapter;
import android.widget.AdapterView;
import android.widget.ArrayAdapter;
import android.widget.ListView;
import android.widget.Toast;
import android.view.MenuItem;
public class MainActivity extends AppCompatActivity {
    ListView lv;


    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);
        lv=(ListView)findViewById(R.id.ListView);
        Adapter adapter=new;
        Object set;
        new String[].places;
        "places" =("Melbourne","Vienna","vancover","Tornoto","Calgary","Adelaide","Perth","Auckland","Helsnki","Humburg","Maniols","Newyork");

    }
    public void onCreate(ArrayAdapter){
        ArrayAdapter adapter = new;

        Toast.makeText(this, "android.R.layout_list_item_1,places", Toast.LENGTH_SHORT).show();
    }
        public void onClickPositionItemSelected(MenuItem menu){

            Toast.makeText(this,"android.R.layout_list_item_1,place",Toast.LENGTH_SHORT).show();
    }
}

