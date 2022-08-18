<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>

  <style>
    a,abbr,acronym,address,applet,article,aside,audio,big,blockquote,body,canvas,caption,center,cite,code,dd,del,details,dfn,div,dl,dt,em,embed,fieldset,figcaption,figure,footer,form,h1,h2,h3,h4,h5,h6,header,hgroup,html,iframe,img,ins,kbd,label,legend,li,mark,menu,nav,object,ol,output,p,pre,q,ruby,s,samp,section,small,span,strike,summary,table,tbody,td,tfoot,th,thead,time,tr,tt,u,ul,var,video{margin:0;padding:0;border:0;font-size:100%;font:inherit;vertical-align:baseline}article,aside,details,figcaption,figure,footer,header,hgroup,menu,nav,section{display:block}body{line-height:1}blockquote,q{quotes:none}blockquote:after,blockquote:before,q:after,q:before{content:'';content:none}table{border-collapse:collapse;border-spacing:0}td,th{background-color:#fff;border:1px solid #ddd;padding:12px 16px;line-height:2em}caption{font-size:1.5em;margin-bottom:12px}input,select{font-size:1rem}button{font-size:1.2rem;margin-right:8px}textarea{padding:8px;font-size:.95em;width:360px;border:1px solid #ddd}label{display:inline-block;margin-right:12px;vertical-align:top}.header{display:grid;grid-template-columns:24px 400px 1fr 84px 24px;grid-template-areas:'left-space logo nav account right-space';align-items:center;height:64px;background-color:#ff4500}.header .logo{grid-area:logo;font-size:2rem;font-weight:700;text-decoration:none;color:#fff}.header .nav{grid-area:nav}.header .nav li{display:inline-block;margin-right:36px}.header .nav li a{font-size:1.25rem;text-decoration:none;color:#fff}.header .account{grid-area:account;font-size:1.5rem;text-decoration:none;color:#fff}.main{display:grid;grid-template-columns:280px 1fr;grid-template-areas:'aside content'}.main .aside{grid-area:aside;background-color:#eee;border-right:1px solid #d3d3d3;padding:36px}.main .aside .option-title{font-size:1.5em;font-weight:700;color:gray}.main .aside ol,.main .aside ul{padding-left:18px;font-size:1.15em;margin:32px 8px;line-height:1.5em}.main .aside ol li,.main .aside ul li{cursor:pointer}.main .content{grid-area:content;min-height:calc(100vh - 196px);background-color:#fafafa}.main .content .section.intro{padding:56px 48px;background-color:#fff;border-bottom:1px solid #d3d3d3;font-size:1.3rem;line-height:1.3em}.main .content .section.intro h1{font-size:1.5em;font-weight:700;margin-bottom:24px}.main .content .section.form{padding:36px}.footer{background-color:#383838;padding:64px 0;font-size:1.2rem;text-align:center}.footer ul>li{display:inline-block;padding:0 48px}.footer ul>li:not(:last-child){border-right:1px solid gray}.footer ul>li a{color:#fff;text-decoration:none}
  </style>
</head>
<body>
  <header class="header">
    <a class="logo" href="#">FastCampus Portfolio</a>
    <nav class="nav">
      <ul>
        <li><a href="#">사진 올리기</a></li>
        <li><a href="#">내 정보</a></li>
        <li><a href="#">팔로우 보기</a></li>
        <li><a href="#">팔로워 보기</a></li>
      </ul>
    </nav>
    <a class="account" href="#">Logout</a>
  </header>
  <main class="main">
    <aside class="aside">
      <div class="option-title">사진 업로드</div>
      <ol>
        <li>양식을 저장한다.</li>
        <li>사진파일을 첨부한다.</li>
        <li>올리기 버튼을 누른다.</li>
      </ol>

    </aside>
    <div class="content">

      <section class="section intro">
        <h1>사진 올리기</h1>
        <p>
            수많은 이용자들이 공유하는 멋진 사진들을 구경하고<br>
            내가 직접 찍은 작품들을 공유하세요!
        </p>
       
      </section>

      <section class="section form">
        <article style="text-align:center">사진 업로드 폼</article>
        <br>
        <div>
            <label>저자정보</label>
            <label for="ip-name">이름</label>
            <input id="ip-name" type="text"/>
            <br>
            <br>

            <input id="id-person" name="type" type="radio" checked/>
            <label for="id-person">일반인</label>
            <input id="id-pro" name="type" type="radio"/>
            <label for="id-pro">전문가</label>
            <br>
            <br>

            <label>사진 정보</label>
            <label for="ip-txt">제목</label>
            <input id="ip-txt" type="text"/>
            <br>
            <br>
            <label for="sel-theme">주제</label>
            <select id="sel-theme">
                <option value="green">자연</option>
                <option vlaue="math">수리</option>
                <option vlaue="org">상경</option>
            </select>
            <br>
            <br>
            <label for="ip-ex">설명</label>
            <textarea id="ipt-ex" placeholder="사진에 담은 생각 등을 자유롭게 적어주세요." rows="10"></textarea>
            <br>
            <Br>
            
            <label for="ip-file">사진 첨부</label>
            <input id="ip-file" type="file"/>
            <br>
            <br>
            <button type="button">올리기</button>
            <button type="button">취소</button>

            

        </div>
        <div>
            <img src="program.jpg" alt="패스트캠퍼스 사진"/>
            <p>
                패스트캠퍼스의 프로그래밍 첫거음 올인원 패키지 강좌로<br>
                여러분의 설레는 첫 코딩을 시작하세요!
            </p>
            <blockquote cite="https://fastcampus.co.kr/?utm_source=google&utm_medium=cpc&utm_campaign=hq^210101^%EC%9E%90%EC%83%81%ED%98%B8&utm_content=%ED%8C%A8%EC%8A%A4%ED%8A%B8%EC%BA%A0%ED%8D%BC%EC%8A%A4&utm_term=&gclid=EAIaIQobChMIl9aTiP3P-QIVRtiWCh2m2gZ-EAAYAiAAEgI4CfD_BwE">

            </blockquote>


        </div>
        
    

   

      </section>

    </div>
  </main>
  <footer class="footer">
    <ul>
      <li><a href="#">회사소개</a></li>
      <li><a href="#">인재채용</a></li>
      <li><a href="#">이용약관</a></li>
      <li><a href="#">개인정보 보호</a></li>
      <li><a href="#">고객센터</a></li>
    </ul>
  </footer>
  
</body>
</html>
