# TableLayout
<TableLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity"
    android:stretchColumns="1"
    android:background="#242424"
    >

    <TableRow>
        <TextView
            android:textColor="#959595"
            android:text="Open...."
            android:paddingLeft="10dp"/>
        <TextView
            android:text="Ctrl+O"
            android:gravity="right"
            android:paddingRight="10dp"/>
    </TableRow>
    <TableRow>
        <TextView
            android:textColor="#959595"
            android:text="Save...."
            android:paddingLeft="10dp"/>
        <TextView
            android:textColor="#959595"
            android:text="Ctrl+S"
            android:gravity="right"
            android:paddingRight="10dp"/>
    </TableRow>
    <TableRow>
        <TextView
            android:textColor="#959595"
            android:text="Save as...."![tablelayout](https://user-images.githubusercontent.com/90606328/135760953-5dff57b0-08d4-498c-9ec4-027741edf809.jpg)
![tablelayout](https://user-images.githubusercontent.com/90606328/135760958-8d13a32b-f64b-401c-9b9e-76f120c7d645.jpg)

            android:paddingLeft="10dp"/>
        <TextView
            android:textColor="#959595"
            android:text="Ctrl+Shift+S"
            android:gravity="right"
            android:paddingRight="10dp"/>
    </TableRow>
    <TableRow>
        <TextView
            android:textColor="#959595"
            android:text="X Import...."
            android:paddingLeft="10dp"/>
    </TableRow>
    <TableRow>
        <TextView
            android:textColor="#959595"
            android:text="X Export...."
            android:paddingLeft="10dp"/>
        <TextView
            android:textColor="#959595"
            android:text="Ctrl+E"
            android:gravity="right"
            android:paddingRight="10dp"/>
    </TableRow>
    <TableRow>
        <TextView
            android:textColor="#959595"
            android:text="  Quit"
            android:paddingLeft="10dp"/>
    </TableRow>
</TableLayout>
