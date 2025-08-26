<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical"
    android:gravity="center"
    android:padding="24dp"
    android:background="#F5F5F5">

    < para o usuário >
    <TextView
        android:id="@+id/tvInstructions"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Digite seu nome, clique no botão e descubra a resposta!"
        android:textSize="18sp"
        android:textColor="#333333"
        android:layout_marginBottom="16dp"
        android:textAlignment="center"/>

    <Campo de entrada do nome>
    <EditText
        android:id="@+id/etNome"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:hint="Digite seu nome"
        android:padding="12dp"
        android:background="@android:drawable/edit_text"
        android:textSize="16sp"
        android:layout_marginBottom="16dp"/>

    < Botão para sortear >
    <Button
        android:id="@+id/btnSortear"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Sortear Resposta"
        android:textSize="16sp"
        android:padding="12dp"
        android:backgroundTint="#6200EE"
        android:textColor="#FFFFFF"
        android:layout_marginBottom="24dp"/>

    < Resultado >
    <TextView
        android:id="@+id/tvResultado"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Sua resposta aparecerá aqui."
        android:textSize="20sp"
        android:textStyle="bold"
        android:textColor="#000000"
        android:layout_marginTop="8dp"/>

</LinearLayout>
