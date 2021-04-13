<template>
<div>
  <b-navbar toggleable="lg" class="nav-style">
    <b-container>
      <img src="../assets/img/dataus-logo.png" alt="DataUs" class="nav-logo">
      <div class="nav-sign">
        <a href="#" class="nec-bar">로그인</a>
        <a href="#">회원가입</a>
      </div>
    </b-container>
      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
        <b-sidebar
          id="nav-collapse"
          title="Sidebar with backdrop"
          :backdrop-variant="variant"
          backdrop
          shadow
        >
            <section>
        <!-- wellcome 이미지 -->
        <article class="art-wellcome">
            <span></span>
            <div class="wellcome-wrap">
                <h1>Wellcom!</h1>
                <p>데이터스 회사 홈페이지</p>
                <button>회사로 바로가기</button>
            </div>
        </article>
        <!-- 검색하기 -->
        <article class="art-earch">
            <h1 class="step01">전체 검색하기</h1>
            <div>
                <input class="search-input" placeholder="Search">
                <button class="search-button" type="submit">Search</button>
            </div>
        </article>
        <!-- 카테고리 -->
        <article class="art-category">
            <h1 class="step02"> 카테고리</h1>
            <div class="category-wrap">
                <ul>
                    <li class="list-checked" ><a href="#">Home</a></li>
                    <li><a href="#">TREND</a></li>
                    <li><a href="#">LIFE</a></li>
                    <li><a href="#">Q&A</a></li>
                </ul>
            </div>
        </article>
        <!-- 태그 검색하기 -->
        <article class="art-search">
            <h1 class="step03">태그 검색하기</h1>
            <div class="list-area">
                <div class="list-search">
                    <div class="search-wrap">
                        <input class="search-input" type="search" placeholder="검색어를 입력해주세요.">
                        <button class="search-button">보내기</button>
                    </div>
                </div>
                <div class="list-wrap">
                    <span></span>
                    <ul>
                        <li class="list-tag list-tag-active">#Javascript</li>
                        <li class="list-tag">#Javascript</li>
                        <li class="list-tag">#Javascript</li>
                        <li class="list-tag">#Javascript</li>
                        <li class="list-tag">#Javascript</li>
                        <li class="list-tag">#Javascript</li>
                        <li class="list-tag">#Javascript</li>
                        <li class="list-tag">#Javascript</li>
                        <li class="list-tag">#Javascript</li>
                    </ul>
                </div>
            </div>
        </article>

    </section>

        </b-sidebar>
  </b-navbar>
</div>

</template>

<script>
export default {
  name: 'NavArea'
}
</script>

