
# Rapport

Skapade en cardview som jag sedan positionerade och la till fler komponenter in i

```
<androidx.cardview.widget.CardView
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:cardBackgroundColor="@color/colorPrimary"
        android:layout_margin="16dp">

```
Exempel på komponenter inne i cardview: Här har vi flera views som ligger i en constraintlayout. "Rubriken" som lyder "Guess the chess piece" är positionerad med hjälp av constraints och layout_marginTop.
```
 <androidx.constraintlayout.widget.ConstraintLayout
        android:id="@+id/card_title"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        android:layout_width="match_parent"
        android:layout_height="72dp">

        <TextView
            android:id="@+id/card_title_text"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_marginTop="16dp"
            android:text="@string/header"
            android:textColor="@color/colorAccent"
            android:textSize="21sp"
            android:textStyle="bold"
            app:layout_constraintStart_toStartOf="parent"
            app:layout_constraintEnd_toEndOf="parent"
            app:layout_constraintTop_toTopOf="parent" />

```

Exempel på komponenter inne i cardview: Här har jag lagt till en edit text ruta och en knapp som man kan klicka på.
```
 <EditText
        android:id="@+id/signIn"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:textColor="@color/colorAccent"
        android:ems="10"
        android:inputType="textPersonName"
        app:layout_constraintTop_toBottomOf="@id/card_body_text"
        app:layout_constraintLeft_toLeftOf="parent"
        app:layout_constraintRight_toLeftOf="@id/signIn_button"
        android:text="@string/textfield" />
        
<Button
        android:id="@+id/signIn_button"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        app:layout_constraintTop_toBottomOf="@id/card_body_text"
        app:layout_constraintStart_toEndOf="@+id/signIn"
        app:layout_constraintEnd_toEndOf="parent"
        android:text="@string/sign_in" />

```
![Screenshot_20240517_123848](https://github.com/b21oscpe/mobileapp-programming-widgets/assets/102578165/ca7c71f7-5a25-4678-9166-e0084b1094c7)

Läs gärna:

- Boulos, M.N.K., Warren, J., Gong, J. & Yue, P. (2010) Web GIS in practice VIII: HTML5 and the canvas element for interactive online mapping. International journal of health geographics 9, 14. Shin, Y. &
- Wunsche, B.C. (2013) A smartphone-based golf simulation exercise game for supporting arthritis patients. 2013 28th International Conference of Image and Vision Computing New Zealand (IVCNZ), IEEE, pp. 459–464.
- Wohlin, C., Runeson, P., Höst, M., Ohlsson, M.C., Regnell, B., Wesslén, A. (2012) Experimentation in Software Engineering, Berlin, Heidelberg: Springer Berlin Heidelberg.
