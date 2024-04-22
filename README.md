
# Rapport

Skapade en constrainlayout och sedan la jag in text som jag positionerade med hjälp av
constraints, t.ex "layout_constraintStart_toEndOf"

Under "Registrera dig" finns det ett "formulär" som egentligen bara har en fråga. formuläret ligger i
en egen constraintlayout.

Positioneringen av mina element gjorde jag med hjälp av constraints samt margins.

```
Här är koden för min nestlade constraintlayout.

<androidx.constraintlayout.widget.ConstraintLayout
        android:id="@+id/form"
        android:layout_width="400dp"
        android:layout_height="wrap_content"
        android:layout_marginTop="20dp"
        app:layout_constraintTop_toBottomOf="@id/form_title"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintEnd_toEndOf="parent">

---

Här är koden jag använde för att göra en radiobutton.

<RadioGroup
            android:id="@+id/radio_gender"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            app:layout_constraintStart_toEndOf="@id/textView4"
            app:layout_constraintTop_toTopOf="parent"
            android:orientation="horizontal">

            <RadioButton android:id="@+id/radio_man"
                android:layout_marginHorizontal="20dp"
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:text="Man" />

```

![](assignment3sc.png)

Läs gärna:

- Boulos, M.N.K., Warren, J., Gong, J. & Yue, P. (2010) Web GIS in practice VIII: HTML5 and the canvas element for interactive online mapping. International journal of health geographics 9, 14. Shin, Y. &
- Wunsche, B.C. (2013) A smartphone-based golf simulation exercise game for supporting arthritis patients. 2013 28th International Conference of Image and Vision Computing New Zealand (IVCNZ), IEEE, pp. 459–464.
- Wohlin, C., Runeson, P., Höst, M., Ohlsson, M.C., Regnell, B., Wesslén, A. (2012) Experimentation in Software Engineering, Berlin, Heidelberg: Springer Berlin Heidelberg.
