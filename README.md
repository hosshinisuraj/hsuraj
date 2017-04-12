@font-face {
  font-family: 'quickweb';
  src: url('../font/quickweb.eot?88707474');
  src: url('../font/quickweb.eot?88707474#iefix') format('embedded-opentype'),
       url('../font/quickweb.woff?88707474') format('woff'),
       url('../font/quickweb.ttf?88707474') format('truetype'),
       url('../font/quickweb.svg?88707474#quickweb') format('svg');
  font-weight: normal;
  font-style: normal;
}
/* Chrome hack: SVG is rendered more smooth in Windozze. 100% magic, uncomment if you need it. */
/* Note, that will break hinting! In other OS-es font will be not as sharp as it could be */
/*
@media screen and (-webkit-min-device-pixel-ratio:0) {
  @font-face {
    font-family: 'quickweb';
    src: url('../font/quickweb.svg?88707474#quickweb') format('svg');
  }
}
*/
 
 [class^="quickweb-icon-"]:before, [class*=" quickweb-icon-"]:before {
  font-family: "quickweb";
  font-style: normal;
  font-weight: normal;
  speak: none;
 
  display: inline-block;
  text-decoration: inherit;
  width: 1em;
  margin-right: .2em;
  text-align: center;
  /* opacity: .8; */
 
  /* For safety - reset parent styles, that can break glyph codes*/
  font-variant: normal;
  text-transform: none;
 
  /* fix buttons height, for twitter bootstrap */
  line-height: 1em;
 
  /* Animation center compensation - margins should be symmetric */
  /* remove if not needed */
  margin-left: .2em;
 
  /* you can be more comfortable with increased icons size */
  /* font-size: 120%; */
 
  /* Font smoothing. That was taken from TWBS */
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
 
  /* Uncomment for 3D effect */
  /* text-shadow: 1px 1px 1px rgba(127, 127, 127, 0.3); */
}
 
.quickweb-icon-monitor:before { content: '\e800'; } /* 'î €' */
.quickweb-icon-desktop-circled:before { content: '\e801'; } /* 'î ' */
.quickweb-icon-desktop:before { content: '\e802'; } /* 'î ‚' */
.quickweb-icon-desktop-1:before { content: '\e803'; } /* 'î ƒ' */
.quickweb-icon-code:before { content: '\e804'; } /* 'î „' */
.quickweb-icon-file-code:before { content: '\e805'; } /* 'î …' */
.quickweb-icon-doc-text:before { content: '\e806'; } /* 'î †' */
.quickweb-icon-doc-inv:before { content: '\e807'; } /* 'î ‡' */
.quickweb-icon-doc-text-inv:before { content: '\e808'; } /* 'î ˆ' */
.quickweb-icon-chart-pie:before { content: '\e809'; } /* 'î ‰' */
.quickweb-icon-chart-line:before { content: '\e80a'; } /* 'î Š' */
.quickweb-icon-chart-area:before { content: '\e80b'; } /* 'î ‹' */
.quickweb-icon-chart-pie-alt:before { content: '\e80c'; } /* 'î Œ' */
.quickweb-icon-heart:before { content: '\e80d'; } /* 'î ' */
.quickweb-icon-lifebuoy:before { content: '\e80e'; } /* 'î Ž' */
.quickweb-icon-clock:before { content: '\e80f'; } /* 'î ' */
.quickweb-icon-bank:before { content: '\e810'; } /* 'î ' */
.quickweb-icon-chart-pie-1:before { content: '\e811'; } /* 'î ‘' */
.quickweb-icon-sliders:before { content: '\e812'; } /* 'î ’' */
.quickweb-icon-lock:before { content: '\e813'; } /* 'î “' */
.quickweb-icon-lock-1:before { content: '\e814'; } /* 'î ”' */
.quickweb-icon-lock-empty:before { content: '\e815'; } /* 'î •' */
.quickweb-icon-cloud:before { content: '\e816'; } /* 'î –' */
.quickweb-icon-cloud-1:before { content: '\e817'; } /* 'î —' */
.quickweb-icon-cloud-thunder:before { content: '\e818'; } /* 'î ˜' */
.quickweb-icon-upload-cloud:before { content: '\e819'; } /* 'î ™' */
.quickweb-icon-cloudapp:before { content: '\e81a'; } /* 'î š' */
.quickweb-icon-smile:before { content: '\e81b'; } /* 'î ›' */
.quickweb-icon-emo-happy:before { content: '\e81c'; } /* 'î œ' */
.quickweb-icon-smiley:before { content: '\e81d'; } /* 'î ' */
.quickweb-icon-smiley-circled:before { content: '\e81e'; } /* 'î ž' */
.quickweb-icon-quote-left:before { content: '\e81f'; } /* 'î Ÿ' */
.quickweb-icon-quote-right:before { content: '\e820'; } /* 'î  ' */
.quickweb-icon-quote-right-1:before { content: '\e821'; } /* 'î ¡' */
.quickweb-icon-quote:before { content: '\e822'; } /* 'î ¢' */
.quickweb-icon-left-circled:before { content: '\e823'; } /* 'î £' */
.quickweb-icon-right-circled:before { content: '\e824'; } /* 'î ¤' */
.quickweb-icon-left-open:before { content: '\e825'; } /* 'î ¥' */
.quickweb-icon-right-open:before { content: '\e826'; } /* 'î ¦' */
.quickweb-icon-right:before { content: '\e827'; } /* 'î §' */
.quickweb-icon-left:before { content: '\e828'; } /* 'î ¨' */
.quickweb-icon-right-open-1:before { content: '\e829'; } /* 'î ©' */
.quickweb-icon-left-open-1:before { content: '\e82a'; } /* 'î ª' */
.quickweb-icon-facebook:before { content: '\e82b'; } /* 'î «' */
.quickweb-icon-facebook-1:before { content: '\e82c'; } /* 'î ¬' */
.quickweb-icon-twitter:before { content: '\e82d'; } /* 'î ­' */
.quickweb-icon-linkedin:before { content: '\e82e'; } /* 'î ®' */
.quickweb-icon-tumblr:before { content: '\e82f'; } /* 'î ¯' */
.quickweb-icon-pinterest:before { content: '\e830'; } /* 'î °' */
.quickweb-icon-gplus:before { content: '\e831'; } /* 'î ±' */
.quickweb-icon-instagram:before { content: '\e832'; } /* 'î ²' */
.quickweb-icon-github-circled:before { content: '\e833'; } /* 'î ³' */
.quickweb-icon-github:before { content: '\e834'; } /* 'î ´' */
.quickweb-icon-flickr:before { content: '\e835'; } /* 'î µ' */
.quickweb-icon-vimeo:before { content: '\e836'; } /* 'î ¶' */
.quickweb-icon-dribbble:before { content: '\e837'; } /* 'î ·' */
.quickweb-icon-skype-circled:before { content: '\e838'; } /* 'î ¸' */
.quickweb-icon-dropbox:before { content: '\e839'; } /* 'î ¹' */
.quickweb-icon-evernote:before { content: '\e83a'; } /* 'î º' */
.quickweb-icon-rdio:before { content: '\e83b'; } /* 'î »' */
.quickweb-icon-lastfm:before { content: '\e83c'; } /* 'î ¼' */
.quickweb-icon-stumbleupon:before { content: '\e83d'; } /* 'î ½' */
.quickweb-icon-behance:before { content: '\e83e'; } /* 'î ¾' */
.quickweb-icon-google-circles:before { content: '\e83f'; } /* 'î ¿' */
.quickweb-icon-instagram-1:before { content: '\e840'; } /* 'î¡€' */
.quickweb-icon-gplus-1:before { content: '\e841'; } /* 'î¡' */
.quickweb-icon-youtube:before { content: '\e842'; } /* 'î¡‚' */
.quickweb-icon-youtube-play:before { content: '\e843'; } /* 'î¡ƒ' */
.quickweb-icon-youtube-squared:before { content: '\e844'; } /* 'î¡„' */
.quickweb-icon-server:before { content: '\e845'; } /* 'î¡…' */
.quickweb-icon-calendar:before { content: '\e846'; } /* 'î¡†' */
.quickweb-icon-ie:before { content: '\e847'; } /* 'î¡‡' */
.quickweb-icon-opera:before { content: '\e848'; } /* 'î¡ˆ' */
.quickweb-icon-chrome:before { content: '\e849'; } /* 'î¡‰' */
.quickweb-icon-firefox:before { content: '\e84a'; } /* 'î¡Š' */
.quickweb-icon-spin4:before { content: '\e84b'; } /* 'î¡‹' */
.quickweb-icon-chart-bar:before { content: '\e84c'; } /* 'î¡Œ' */
.quickweb-icon-chart-line-1:before { content: '\e84d'; } /* 'î¡' */
.quickweb-icon-chart-pie-2:before { content: '\e84e'; } /* 'î¡Ž' */
.quickweb-icon-chart-area-1:before { content: '\e84f'; } /* 'î¡' */
.quickweb-icon-gauge:before { content: '\e850'; } /* 'î¡' */
.quickweb-icon-sitemap:before { content: '\e851'; } /* 'î¡‘' */
.quickweb-icon-soccer-ball:before { content: '\e852'; } /* 'î¡’' */
.quickweb-icon-wechat:before { content: '\e853'; } /* 'î¡“' */
.quickweb-icon-check:before { content: '\e854'; } /* 'î¡”' */
.quickweb-icon-cancel:before { content: '\e855'; } /* 'î¡•' */
.quickweb-icon-brush:before { content: '\e856'; } /* 'î¡–' */
.quickweb-icon-globe:before { content: '\e857'; } /* 'î¡—' */
.quickweb-icon-mail-alt:before { content: '\e858'; } /* 'î¡˜' */
.quickweb-icon-mail-squared:before { content: '\e859'; } /* 'î¡™' */
.quickweb-icon-mail:before { content: '\e85a'; } /* 'î¡š' */
.quickweb-icon-mail-1:before { content: '\e85b'; } /* 'î¡›' */
.quickweb-icon-phone:before { content: '\e85c'; } /* 'î¡œ' */
.quickweb-icon-phone-1:before { content: '\e85d'; } /* 'î¡' */
.quickweb-icon-mobile:before { content: '\e85e'; } /* 'î¡ž' */
.quickweb-icon-location:before { content: '\e85f'; } /* 'î¡Ÿ' */
.quickweb-icon-direction:before { content: '\e860'; } /* 'î¡ ' */
.quickweb-icon-location-inv:before { content: '\e861'; } /* 'î¡¡' */
.quickweb-icon-location-1:before { content: '\e862'; } /* 'î¡¢' */
.quickweb-icon-address:before { content: '\e863'; } /* 'î¡£' */
