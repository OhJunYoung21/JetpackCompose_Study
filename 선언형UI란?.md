# 선언형 UI란 무엇인가?

# 명령형UI가 아닌 선언형UI 프로그래밍이 바로 JetpackCompose의 장점이다.

<div>아래의 코드는 안드로이드 스튜디오에서 프로젝트를 생성하면 자동으로 주어지는 activity_main.xml파일이다.</div>
<div>큰 의미는 없으며, 단지 메인화면의 UI를 나타낸 것이다.</div>

~~~xml
<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Hello World!"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent" />

</androidx.constraintlayout.widget.ConstraintLayout>
~~~
