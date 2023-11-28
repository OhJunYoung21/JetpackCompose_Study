# 명령형 UI프로그래밍과 선언혀UI프로그래밍

## 명령형 프로그래밍(기존의 프로그래밍)


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
<div>기존의 프로그래밍에서는 사용자와의 상호작용등의 이유로 앱 내의 데이터가 변경되는 경우, UI계층 트리를 탐색하여 UI를 업데이트했어야 했습니다.</div>

<div>예를 들면, findViewById<R.id.button1>로 객체애 할당된 아이디를 사용하거나, Gradle파일에서 ViewBinding = true를 선언해준 다음 뷰바인딩을 사용하는 방법이 있었습니다.
</div>
