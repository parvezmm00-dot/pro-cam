<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout 
    xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:background="#000000">

    <androidx.camera.view.PreviewView
        android:id="@+id/previewView"
        android:layout_width="0dp"
        android:layout_height="0dp"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintBottom_toTopOf="@id/bottomControls"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintEnd_toEndOf="parent" />

    <!-- Filter buttons -->
    <HorizontalScrollView
        android:id="@+id/filterScroll"
        android:layout_width="0dp"
        android:layout_height="wrap_content"
        android:scrollbars="none"
        android:padding="8dp"
        app:layout_constraintBottom_toTopOf="@id/bottomControls"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintEnd_toEndOf="parent">

        <LinearLayout
            android:id="@+id/filterContainer"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:orientation="horizontal">

            <Button android:id="@+id/btnNatural" android:layout_width="wrap_content" android:layout_height="40dp" android:text="Natural" android:layout_marginEnd="8dp" android:textSize="12sp"/>
            <Button android:id="@+id/btnVivid" android:layout_width="wrap_content" android:layout_height="40dp" android:text="Vivid" android:layout_marginEnd="8dp" android:textSize="12sp"/>
            <Button android:id="@+id/btnWarm" android:layout_width="wrap_content" android:layout_height="40dp" android:text="Warm" android:layout_marginEnd="8dp" android:textSize="12sp"/>
            <Button android:id="@+id/btnCool" android:layout_width="wrap_content" android:layout_height="40dp" android:text="Cool" android:layout_marginEnd="8dp" android:textSize="12sp"/>
            <Button android:id="@+id/btnContrast" android:layout_width="wrap_content" android:layout_height="40dp" android:text="Contrast" android:textSize="12sp"/>

        </LinearLayout>
    </HorizontalScrollView>

    <!-- Bottom controls -->
    <LinearLayout
        android:id="@+id/bottomControls"
        android:layout_width="0dp"
        android:layout_height="110dp"
        android:orientation="horizontal"
        android:gravity="center"
        android:background="#E6000000"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintEnd_toEndOf="parent">

        <Button
            android:id="@+id/btnSwitch"
            android:layout_width="70dp"
            android:layout_height="70dp"
            android:text="⇄"
            android:textSize="22sp"
            android:layout_marginEnd="40dp"/>

        <Button
            android:id="@+id/btnCapture"
            android:layout_width="80dp"
            android:layout_height="80dp"
            android:text="●"
            android:textSize="28sp"
            android:backgroundTint="#FFFFFF"/>

    </LinearLayout>

</androidx.constraintlayout.widget.ConstraintLayout>
