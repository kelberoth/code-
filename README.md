</head>

<body>
    <h1>jQuery + Javascript의 조합을 연습하자!</h1>

    <div class="question-box">
        <h2>1. 빈칸 체크 함수 만들기</h2>
        <h5>1-1. 버튼을 눌렀을 때 입력한 글자로 얼럿 띄우기</h5>
        <h5>[완성본]1-2. 버튼을 눌렀을 때 칸에 아무것도 없으면 "입력하세요!" 얼럿 띄우기</h5>
        <input id="input-q1" type="text" /> <button onclick="q1()">클릭</button>
    </div>

     
     10번에서 id 값을 호출 
     id 값은 21번부터 내용 정리 
     
     </style>

    <script>
        function q1() {
            let txt = $('#input-q1').val();
            if(txt == '') {
                alert('입력하세요!')
            } else {
                alert(txt)
            }
