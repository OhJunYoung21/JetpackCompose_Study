# Compose를 사용해서 아이디, 비밀번호 찾기를 구현해보자.

XML을 사용하지 않는 것이 Compose의 특징이다. 코틀린 코드내에서 UI를 만들기 때문이다. 이는 선언현 UI의 특징이다.

~~~kotlin
override fun onCreate(savedInstanceState: Bundle?) {
        super.onCreate(savedInstanceState)
        setContent {
            Running_BetaTheme {
                // A surface container using the 'background' color from the theme
                Surface(
                    modifier = Modifier.fillMaxSize(),
                    color = MaterialTheme.colorScheme.background
                ) {
                    Greeting("Android")
                }
            }
        }
    }
~~~
