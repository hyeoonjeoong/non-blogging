![logo](https://github.com/hyunhokimm/non-blogging/assets/129264045/e5d8f321-5495-4061-978c-179b77e7ce6f)

<br />
<h3 id="infoProject">📜(n)on-blogging?</h3>
<p id="introProject">
blogging is happy. enjoy✌️
<hr />
  <div>
   <h4>
     ✨ 블로그를 통해 의견을 표현하고 다른 사람과 소통을 할 수 있는 블로그 웹사이트입니다.
   </h4>

◦ 메인 페이지 : 친구의 블로그와 포스팅 확인 <br/>
◦ 로그인, 로그아웃, 회원가입, 마이페이지 관리 <br/>
◦ 게시글 업로드, 수정, 삭제 <br/>
◦ 댓글 작성, 수정, 삭제 <br/>
  </div>

<hr />
✿ Enjoy & Happy to BLog '◡'✿</p>

<br />
<h3 id="pjMember">🫱🏻‍🫲🏻Member</h3>
<div id="hh" style="text-weight: bold">김현호</div>
  <ul>
    <li>Full</li>
    <li><img src="https://img.shields.io/badge/-181717?style=flat-square&logo=GitHub&logoColor=white"/>
: <a href="https://github.com/hyunhokimm" target="_blank">@hyunhokimm</a></li>
  </ul>
<div id="KrillM" style="text-weight: bold">명길식</div>
  <ul>
    <li>BACK</li>
    <li><img src="https://img.shields.io/badge/-181717?style=flat-square&logo=GitHub&logoColor=white"/>: <a href="https://github.com/KrillM" target="_blank">@KrillM</li>
  </ul>
<div id="hyeoonjeoong" style="text-weight: bold">양현정</div>
  <ul>
    <li>FRONT</li>
    <li><img src="https://img.shields.io/badge/-181717?style=flat-square&logo=GitHub&logoColor=white"/>: <a href="https://github.com/hyeoonjeoong" target="_blank">@hyeoonjeoong</li>
  </ul>
<div id="siri" style="text-weight: bold">이은실</div>
  <ul>
    <li>BACK</li>
    <li><img src="https://img.shields.io/badge/-181717?style=flat-square&logo=GitHub&logoColor=white"/>: <a href="https://github.com/heysirilee" target="_blank">@heysirilee</li>
  </ul>

<br />
<h3 id="useTechStack">✏️Technologies and tools used</h3>
<div>
  <p>EJS</p>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=HTML5&logoColor=white" />
  <br />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=CSS3&logoColor=white" />
  <br />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=JavaScript&logoColor=white" />
  <br />
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white" />
  <br />
  <img src="https://img.shields.io/badge/Nodemon-76D04B?style=flat&logo=nodemon&logoColor=white" />
  <br />
  <img src="https://img.shields.io/badge/Express-FFFFFF?style=flat&logo=express&logoColor=black" />
  <br />
  <img src="https://img.shields.io/badge/mySql-4479A1?style=flat&logo=mysql&logoColor=white" />
  <br />
  <img src="https://img.shields.io/badge/VisualStudioCode-007ACC?style=flat&logo=Visual%20Studio%20Code&logoColor=white" />
</div>

<br />
<h3 id="getStart">✏️Installation method</h3>
<p>Develop 서버 실행</p>
  <pre><code>
    npm i
    npm run dev
  </code></pre>
<p>Production 서버 실행</p>
   <pre><code>
    npm i
    npm run start
    </code></pre>

<h3 id="folderStructure">🗂️Folder Structure</h3>
    <pre><code>
    📦non-blogging
 ┣ 📂config
 ┃ ┣ 📂envs
 ┃ ┃ ┗ 📜.env
 ┃ ┗ 📜index.json
 ┣ 📂controller
 ┃ ┣ 📜Cblogging.js
 ┃ ┣ 📜Chome.js
 ┃ ┣ 📜Clogin.js
 ┃ ┣ 📜Cmyblog.js
 ┃ ┣ 📜CmyInfo.js
 ┃ ┣ 📜Cmypost.js
 ┃ ┗ 📜Csignup.js
 ┣ 📂model
 ┃ ┣ 📜Comment.js
 ┃ ┣ 📜index.js
 ┃ ┣ 📜Notebook.js
 ┃ ┗ 📜User.js
 ┣ 📂node_modules
 ┣ 📂routes
 ┃ ┣ 📂note
 ┃ ┃ ┗ 📜index.js
 ┃ ┗ 📂user
 ┃ ┃ ┗ 📜index.js
 ┣ 📂static
 ┃ ┣ 📂images
 ┃ ┣ 📜allblog.js
 ┃ ┗ 📜logo.png
 ┣ 📂uploads
 ┣ 📂views
 ┃ ┣ 📂fragment
 ┃ ┃ ┣ 📜blog.ejs
 ┃ ┃ ┣ 📜footer.ejs
 ┃ ┃ ┣ 📜functions.ejs
 ┃ ┃ ┣ 📜header.ejs
 ┃ ┃ ┗ 📜nonote.ejs
 ┃ ┣ 📜allblog.ejs
 ┃ ┣ 📜login.ejs
 ┃ ┣ 📜main.ejs
 ┃ ┣ 📜myInfo.ejs
 ┃ ┣ 📜note.ejs
 ┃ ┣ 📜notebook.ejs
 ┃ ┣ 📜signUp.ejs
 ┃ ┗ 📜write.ejs
 ┣ 📜.gitignore
 ┣ 📜index.js
 ┣ 📜package.json
 ┗ 📜README.md
    </code></pre>

<h2>And Happy coding, everyone ✌️</h2>
