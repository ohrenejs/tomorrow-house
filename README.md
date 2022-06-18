# GNB

- 로그인 했을 때

```html
<div class="btn-group">
  <button
    type="button"
    class="lg-hidden gnb-icon-btn is-search"
    aria-label="검색창 열기 버튼"
  >
    <i class="i-search"></i>
  </button>

  <a href="./" class="sm-hidden gnb-icon-btn" aria-label="북마크 페이지로 이동">
    <i class="i-bookmark"></i>
  </a>
  <a
    href="./"
    class="sm-hidden gnb-icon-btn"
    aria-label="내 소식 페이지로 이동"
  >
    <i class="i-bell"></i>
  </a>
  <a href="./" class="gnb-icon-btn" aria-label="장바구니 페이지로 이동">
    <i class="i-cart"></i>
    <strong class="badge">5</strong>
  </a>

  <button
    type="button"
    class="sm-hidden gnb-avater-btn avatar-32"
    aria-label="마이메뉴 열기 버튼"
  >
    <img src="./assets/images/img-user-01.jpg" alt="사달라 아저씨" />
  </button>
</div>
```

- 로그인 하지 않았을 때

```html
<div class="btn-group">
  <button
    type="button"
    class="lg-hidden gnb-icon-btn is-search"
    aria-label="검색창 열기 버튼"
  >
    <i class="i-search"></i>
  </button>

  <a href="./" class="gnb-icon-btn" aria-label="장바구니 페이지로 이동">
    <i class="i-cart"></i>
  </a>

  <div class="sm-hidden gnb-auth">
    <a href="./">로그인</a>
    <a href="./">회원가입</a>
  </div>
</div>
```
