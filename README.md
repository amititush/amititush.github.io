@import url(https://mwittrien.github.io/BetterDiscordAddons/Themes/BlurpleRecolor/BlurpleRecolor.css);

:root {
	--dtransparencycolor: 0,0,0;
	--dtransparencyalpha: 0.15;
	--dmessagetransparency: 0.5;
	--dguildchanneltransparency: 0.15;
	--dmemberlistransparency: 0.0;
	--daccentcolor: 190,78,180;
	--dbackground: url(https://mwittrien.github.io/BetterDiscordAddons/ThemesV2/BasicBackground/background.jpg);
	--dbackdrop: rgba(0,0,0,0.4);
	--dblur: 0px;
	--vtransparencycolor: var(--transparencycolor,var(--dtransparencycolor));
	--vtransparencyalpha: var(--transparencyalpha,var(--dtransparencyalpha));
	--vmessagetransparency: var(--messagetransparency,var(--dmessagetransparency));
	--vguildchanneltransparency: var(--guildchanneltransparency,var(--dguildchanneltransparency));
	--vmemberlistransparency: var(--memberlistransparency,var(--dmemberlistransparency));
	--vaccentcolor: var(--accentcolor,var(--daccentcolor));
	--vbackground: var(--background,var(--dbackground));
	--vbackdrop: var(--backdrop,var(--dbackdrop));
	--vbackgroundblur: var(--backgroundblur,var(--dblur));
	--vpopoutblur: var(--popoutblur,var(--dblur));
	--vbackdropblur: var(--backdropblur,var(--dblur));
}

.container-16j22k:before,
.appMount-3lHmkl:before {
	content: "";
	top: 0;
	left: 0;
	right: 0;
	bottom: 0;
	position: absolute;
	background: var(--vbackground) center/cover !important;
	filter: blur(var(--vbackgroundblur)) !important;
}

.wrapper-3Q5DdO {
	background: rgba(var(--vtransparencycolor),calc(var(--vtransparencyalpha) * 3)) !important;
}
.wrapper-3Q5DdO > .rightSplit-2US0xy > .image-2jyRAK,
.wrapper-3Q5DdO > .rightSplit-2US0xy + .canvas-3XuBXe {
	display: none !important;
}

.uploadArea-3QgLtW,
.backdrop-1wrmKB {
	background: var(--vbackdrop) center/cover !important;
	filter: blur(var(--vbackdrop)) !important;
	opacity: 1 !important;
	animation: none !important;
}

.pageWrapper-1PgVDX,
.noChannel-Z1DQK7,
.activityFeed-28jde9,
.gameLibrary-TTDw4Y,
.applicationStore-1pNvnv,
.lfg-3xoFkI,
.root-1BQpZw,
.app-2rEoOp,
.layers-3iHuyZ,
.layer-3QrUeG,
.container-2lgZY8,
.contentWrapper-3WC1ID,
.popout-3sVMXz section,
.contentRegion-3nDuYy,
.container-3gCOGc .tabBar-1E2ExX .item-PXvHYJ:hover,
.input-cIJ7To,
.item-26Dhrx:not([style*="rgb(114, 137, 218)"]) .checked-3_4uQ9,
.containerUserOver-1U5YnL:after,
.chat-3bRxxu .inner-zqa7da,
.messageGroupBlocked-3wrQQX,
.action-1lSjCi,
.or-3THJsp,
.quickSelectPopoutOption-opKBx9:not(.selected):hover,
.embedInner-1-fpTo,
.changeDetails-bk98pu,
.paginationItem-2lUq0s:not(.selectedPage-3cFHgU),
.Select-control,
.form-inner,
.wrapper-29NfPK,
.searchBar-2_Yu-C,
.search-l1Wz-Q .search-bar,
.searchResultsWrap-2DKFzt,
.searchResultsWrap-2DKFzt .searchHeader-1l-wpR,
.sidebarRegion-VFTUkN,
:not(.tab-content) > .standardSidebarView-3F1I7i,
.card-3Qj_Yx,
.container-1UB9sr,
.container-2Thooq,
.listeningAlong-2UPsxf,
.reactors-Blmlhw {
	background: rgba(var(--vtransparencycolor),var(--vtransparencyalpha)) !important;
}

.sidebar-1-SQro {
	background: rgba(var(--vtransparencycolor),calc(var(--vtransparencyalpha) * 2)) !important;
}

.base-3dtUhz {
	border-radius: 0 !important;
}

.tutorial-popout .title-content,
.modal-1UGdnR .header,
.modal-1UGdnR .footer,
.wrapper-1prNyd,
.popout-3sVMXz header,
.popout-3sVMXz .header,
.popout-3sVMXz .header-ykumBX,
.popout-3sVMXz .footer,
.popout-3sVMXz .footer-1kmXd4,
.authBox-hW6HRx,
.date-picker-hint,
.card-7JP0BX,
.card-7JP0BX .header-1RC2Wb,
.carousel-JbsNzL,
.carousel-2WxMes,
.smallCarousel-3UDi9v,
.smallCarousel-2e0IQc,
.article-FleDq5,
.container-2Zlzt0,
.selectedPage-3cFHgU,
.gameUpdates-2GPqBU,
.root-1bFE0x,
.bodySection-jqkkIP,
.row-1bU71H,
.option-1l2vXE,
.focused-1Yu0L3,
.expandedInfo-3kfShd,
.defaultIndicator-2X8Auf,
.applicationTile-1Goy1W,
.tile-2OwFgW,
.tileMedia-1q3guD,
.news-2GDtLJ,
.modal-3HD5ck,
.modal-3HD5ck .header-1R_AjF,
.modal-3HD5ck .footer-2yfCgX,
.divider-3573oO,
.divider-1pnAR2,
.guildInner-3DSoA4,
.header-GwIGlr,
.itemDefault-3Jdr52:not(.tabBarItem-1b8RUP):not(.tabBarItem-1Cg-MI):hover,
.selectableItem-1MP3MQ:hover,
.friend:hover,
.ui-tab-bar-item:hover,
.friendsRow-2yicud:hover,
.channel-2QD9_O:hover a,
.member-3W1lQa:hover .content-OzHfo4,
.member-3W1lQa.popout-open .content-OzHfo4,
.input-3yHnCz,
.attachment-33OFj0,
.wrapperHoveredCollapsed-1PADEo,
.wrapperHovered-28fu1D,
.wrapperLockedVoice-3QrBs-:hover .content-20Aix8,
.wrapperHoveredVoice-3ItgyI .content-20Aix8,
.wrapperHoveredText-2geN_M .content-20Aix8,
.userHovered-2_fT4Z,
.container-1YxwTf .inline,
.container-1YxwTf pre,
.messageGroupBlockedBtn-1PBBh-,
.number-3ceIrJ,
.result-2S5Awv:after,
.body-1CAT0-,
.body-1SVoBw,
.content-35aVm0,
.card-NB61oR,
.bubble-1gL_TN,
.bda-slist li,
.uploadModal-2ifh8j .inner-zqa7da,
.cardPrimary-1Hv-to,
.cardPrimaryOutline-29Ujqw,
.searchBox-3Y2Vi7,
.selectorSelected-1_M1WV,
#autocomplete-popout .row.selected,
.friendSelected--wQP3f,
.paginator-166-09,
.emptyHintCard-2mUdMe,
.categoryFade-2ybR1J,
.quickSelectPopoutOption-opKBx9.selected,
.payment-xT17Mq,
.tier1Banner-1B_WXY,
.paymentPane-3bwJ6A,
.wrapper-39oAo3,
.gameNameInput-385LoS:hover,
.gameNameInput-385LoS:focus,
.selectableItem-1MP3MQ:hover,
.notDetected-33MY4s,
.dockItem-2kQDqg:hover,
.previewOverlay-2O7_KC,
.wrapper-29NfPK .actions-2vadYq .center-1Vp33r,
.searchResultsWrap-2DKFzt .searchResultMessage-2VxO12.hit-NLlWXA,
.embed-IeVjo6,
.personalizationNotice-2HTAH2,
.rowWrapperActive-2L7i9f,
.emptyState-2-sT0o,
.btn-11C5_u,
.wrapper-35wsBm,
.wrapper-2TxpI8,
.tiles-2aXG_k,
.inviteRow-2L02ae:hover,
.audioControls-2HsaU6,
.invite-18yqGF,
.close-18n9bP:hover,
.guildSeparator-1X4GQ1:after,
.guildsAdd-21_IdK {
	border-color: transparent !important;
	background: rgba(var(--vtransparencycolor),calc(var(--vtransparencyalpha) * 3)) !important;
}

.searchBoxInputWrapper-nKncfu {
	padding-right: 16px !important;
}

.check-2by_h9 {
	-webkit-mask: url(https://discordapp.com/assets/6acb20d5e709b34b6a7f36ec13648666.svg) center/cover no-repeat !important;
	background: rgb(var(--vaccentcolor)) !important;
}
.applicationStore-1pNvnv .home-2gmu2h {
	padding-top: 5px;
}
.itemBackground-2vEldQ,
.itemBackground-1jfD8p {
	border-radius: 9px;
	background-color: rgba(var(--vtransparencycolor),calc(var(--vtransparencyalpha) * 3)) !important;
}
.itemBackground-2vEldQ:before,
.itemBackground-1jfD8p:before {
	border-radius: 9px;
	background: radial-gradient(ellipse at top,transparent,rgba(var(--vtransparencycolor),calc(var(--vtransparencyalpha) * 4))),linear-gradient(90deg,rgba(var(--vtransparencycolor),calc(var(--vtransparencyalpha) * 4)) 0,transparent 40%,transparent 60%,rgba(var(--vtransparencycolor),calc(var(--vtransparencyalpha) * 4))),linear-gradient(0deg,rgba(var(--vtransparencycolor),calc(var(--vtransparencyalpha) * 4)) 0,transparent 25%) !important;
}
.paginationItem-2r4mQd {
	background: url('data:image/svg+xml; utf8, <svg xmlns:xlink="http://www.w3.org/1999/xlink" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 26 26" version="1.1" width="36" height="36"><path fill="#FFF" d="M2.98966977,9.35789159 C2.98966977,9.77582472 2.63442946,10.1240466 2.20807287,10.1240466 L1.78171628,10.1240466 C1.35535969,10.1240466 0.999948837,9.77582472 0.999948837,9.35789159 C0.999948837,8.93995846 1.35535969,8.59173658 1.78171628,8.59173658 L2.20807287,8.59173658 C2.63442946,8.59173658 2.98966977,8.93995846 2.98966977,9.35789159 Z M22.2467643,9.14892503 C24.0942527,12.9800344 22.3888264,17.5772989 18.3384388,19.3882867 C14.4302837,21.1297305 9.74036124,19.457998 7.9638186,15.6268886 C7.60857829,14.8607335 7.3954,14.0248673 7.32428372,13.189001 L5.76091938,13.189001 C5.33456279,13.189001 4.97932248,12.840612 4.97932248,12.4226788 C4.97932248,12.0047457 5.33456279,11.6565238 5.76091938,11.6565238 L8.03493488,11.6565238 C8.46129147,11.6565238 8.81653178,11.3083019 8.81653178,10.8903688 C8.81653178,10.4724357 8.46129147,10.1240466 8.03493488,10.1240466 L4.41090388,10.1240466 C3.98454729,10.1240466 3.62913643,9.77582472 3.62913643,9.35789159 C3.62913643,8.93995846 3.98454729,8.59173658 4.41090388,8.59173658 L9.45606667,8.59173658 C9.88242326,8.59173658 10.2376636,8.24334752 10.2376636,7.82541439 C10.2376636,7.40748126 9.88242326,7.05925937 9.45606667,7.05925937 L7.3954,7.05925937 C6.75586512,7.05925937 6.18727597,6.57161499 6.18727597,5.87517123 C6.18727597,5.24827153 6.68474884,4.69091591 7.3954,4.69091591 L15.4250589,4.69091591 C18.267493,4.8303384 20.9676946,6.43235968 22.2467643,9.14892503 Z M13.2662961,8.38056332 C11.0193969,9.3919615 10.0341721,11.9973566 11.065955,14.1998642 C12.097738,16.4023718 14.755645,17.3681317 17.0025442,16.3567335 C19.249614,15.3453354 20.2346682,12.7399402 19.2028853,10.5374326 C18.1711023,8.33492503 15.5131953,7.36916515 13.2662961,8.38056332 Z M16.8462589,9.84548582 L18.2673907,12.2138293 C18.338507,12.3530846 18.338507,12.4227958 18.2673907,12.5620512 L16.8462589,14.9303946 C16.7751426,15.0696499 16.6330806,15.0696499 16.5619643,15.0696499 L13.7906465,15.0696499 C13.6485845,15.0696499 13.5774682,14.9999387 13.5065225,14.9303946 L12.0852202,12.5620512 C12.0142744,12.4227958 12.0142744,12.3530846 12.0852202,12.2138293 L13.5065225,9.84548582 C13.5774682,9.7062305 13.7197008,9.7062305 13.7906465,9.7062305 L16.5619643,9.7062305 C16.7041969,9.63651925 16.7751426,9.7062305 16.8462589,9.84548582 Z"></path></svg>') center no-repeat !important;
	object-position: -999px -999px;
}

.paginationItem-2lUq0s:after {
	background: linear-gradient(270deg,transparent 0,rgba(var(--vtransparencycolor),calc(var(--vtransparencyalpha) * 3))) !important;
}
.paginationItem-2lUq0s .splashArt-1anaP9 {
	border-radius: 5px !important;
}

.container-2VW0UT {
	background: rgba(var(--vtransparencycolor),0.8) !important;
}

.bar-2Qqk5Z {
	padding: 1px;
}

.distributionApplicationsActions-3D2_kD,
.premiumApplicationsHeader-Zmkm5e,
.headerPurchase-2z_nch,
.row-1bU71H,
.divider-21LyPb,
.sortFilterBar-3hePOV,
.headerText-2niCs_,
.Select-control,
.messageGroupBlocked-3wrQQX,
.input-cIJ7To:not(:focus),
.container-1UB9sr,
.cardPrimaryEditable-3KtE4g {
	border-color: rgba(var(--vtransparencycolor),calc(var(--vtransparencyalpha) * 3)) !important;
}

.Select-control:hover {
	border-color: rgba(var(--vtransparencycolor),calc(var(--vtransparencyalpha) * 6)) !important;
}

.installationPath-24giJj {
	box-shadow: 0 1px 0 0 rgba(var(--vtransparencycolor),calc(var(--vtransparencyalpha) * 3)) !important;
}

.message-2qRu38 {
	box-shadow: none !important;
	border: none !important;
	border-radius: 5px !important;
	background: rgba(var(--vtransparencycolor),calc(var(--vtransparencyalpha) * 2)) !important;
	padding-left: 10px;
}

.emojiButtonNormal-TdumYh {
	opacity: 0.5 !important;
}

input:disabled {
	background: rgba(var(--vtransparencycolor),calc(var(--vtransparencyalpha) * 3)) !important;
	filter: brightness(50%) !important;
}

.linkButtonIcon-Mlm5d6:not([style*="color"]),
.nameSelectedText-sp_EUw:not([style*="color"]),
.nameHoveredText-1uO31y:not([style*="color"]),
.nameSelectedVoice-1qSph5:not([style*="color"]),
.nameHoveredVoice-YJ1Vfd:not([style*="color"]) {
	color: rgb(255,255,255) !important;
}
.colorSelectedText-1y4Wvs:not([style*="color"]) path,
.colorHoveredText-OZnAgu:not([style*="color"]) path,
.colorSelectedVoice-Xcb_9R:not([style*="color"]) path,
.colorHoveredVoice-1kucsK:not([style*="color"]) path {
	color: rgb(255,255,255) !important;
	opacity: 1 !important;
}
.messages-popout-wrap {
	width: 500px !important;
}

.content-Qb0rXO {
	color: #f6f6f7 !important;
}

.keybindShortcut-1BD6Z1 span {
	color: hsla(0,0%,100%,.8) !important;
	background: rgba(var(--vaccentcolor),0.3) !important;
	border-color: rgb(var(--vaccentcolor)) !important;
	box-shadow: inset 0 -4px 0 rgba(var(--vaccentcolor),0.5) !important;
}
.keybindShortcut-1BD6Z1 [fill]:not([fill="none"]) {
	fill: hsla(0,0%,100%,.8) !important;
}
.keybindShortcut-1BD6Z1 [stroke]:not([stroke="none"]) {
	stroke: hsla(0,0%,100%,.8) !important;
}

.actionButtons-1sUUug {
	top: 5px !important;
	right: 15px !important;
}
.actionButtons-14P9IC,
.search-result .action-buttons {
	right: 20px !important;
}
.action-buttons .jump-button,
.actionButtons-14P9IC .jumpButton-Ia2hRJ,
.actionButtons-1sUUug .jumpButton-3DTcS_,
.action-buttons .close-button,
.actionButtons-1sUUug .closeButton-17RIVZ {
	border-radius: 3px !important;
	height: 14px !important;
	margin: 0 3px !important;
	padding: 3px !important;
	background-color: rgba(var(--vtransparencycolor),calc(var(--vtransparencyalpha) * 3)) !important;
}
.container-1YxwTf:hover .jump-button,
.container-1YxwTf:hover .close-button,
.container-1YxwTf:hover .jumpButton-Ia2hRJ,
.container-1YxwTf:hover .jumpButton-3DTcS_,
.container-1YxwTf:hover .closeButton-17RIVZ {
	opacity: 0.5 !important;
}
.container-1YxwTf .jump-button:hover,
.container-1YxwTf .close-button:hover,
.container-1YxwTf .jumpButton-Ia2hRJ:hover,
.container-1YxwTf .jumpButton-3DTcS_:hover,
.container-1YxwTf .closeButton-17RIVZ:hover {
	opacity: 1 !important;
}
.action-buttons .text,
.actionButtons-14P9IC *,
.actionButtons-1sUUug * {
	color: rgb(255,255,255) !important;
}

.card-FDVird {
	margin: 0 0 6px 0 !important;
}
.card-FDVird:before {
	border: none !important;
	opacity: 1 !important;
	background: rgba(var(--vtransparencycolor),var(--vtransparencyalpha)) !important;
	transition: background .1s ease !important;
}

.card-FDVird:hover:before {
	background: rgba(var(--vtransparencycolor),calc(var(--vtransparencyalpha) * 3)) !important;
}

.layer-3QrUeG[aria-label="GUILD_SETTINGS"] .card-FDVird {
	left: 20px !important;
}

.divider-3gKybi:not(.dividerRed-MKoLlr) .dividerContent-2L12VI {
	color: rgb(200,200,200) !important;
}
.divider-3gKybi.dividerRed-MKoLlr .dividerContent-2L12VI {
	color: rgb(var(--vaccentcolor)) !important;
}
.divider-3gKybi:not(.dividerRed-MKoLlr) .dividerContent-2L12VI:after, 
.divider-3gKybi:not(.dividerRed-MKoLlr) .dividerContent-2L12VI:before {
	border-color: rgb(200,200,200) !important;
}
.divider-3gKybi.dividerRed-MKoLlr .dividerContent-2L12VI:after, 
.divider-3gKybi.dividerRed-MKoLlr .dividerContent-2L12VI:before {
	border-color: rgba(var(--vaccentcolor),.4) !important;
}
.divider-3gKybi .dividerContent-2L12VI {
	background: rgba(var(--vtransparencycolor),var(--vmessagetransparency)) !important;
	border-radius: 5px !important;
}
.divider-3gKybi .dividerContent-2L12VI:after, 
.divider-3gKybi .dividerContent-2L12VI:before {
	margin: 0 8px !important;
}
.containerCozy-jafyvG {
	overflow: visible !important;
	padding: 10px 0 !important;
	margin: 10px 5px 10px 80px !important;
	border-radius: 5px !important;
	background: rgba(var(--vtransparencycolor),var(--vmessagetransparency)) !important;
}
.headerCozy-2N9HOL {
	position: relative !important;
	margin-left: 10px !important;
}
.headerCozy-2N9HOL .avatar-17mtNa {
	position: absolute !important;
	left: -90px !important;
	top: 0 !important;
}
.headerCozy-2N9HOL .avatar-17mtNa:after {
	content: "";
	position: relative;
	float: left;
	left: 35px;
	top: -30px;
	width: 0;
	height: 0;
	border: 10px solid transparent;
	border-right: 15px solid rgba(var(--vtransparencycolor),var(--vmessagetransparency));
}
.contentCozy-3XX413 {
	margin-left: 10px !important;
}
.containerCompact-3V0ioj {
	margin: 5px;
	padding: 5px 0 !important;
	border-radius: 5px !important;
	background: rgba(var(--vtransparencycolor),var(--vmessagetransparency)) !important;
}
.containerCompact-3V0ioj + .divider-3gKybi {
	top: 5px;
}
.divider-3gKybi + .containerCompact-3V0ioj {
	margin-top: 15px !important;
}
.container-1YxwTf.containerCompact-3V0ioj .messageCozy-2JPAPA {
	padding: 0 !important;
}
.container-1YxwTf .inline {
	padding: 0.6px 5px !important;
}

.channelNotice-1-XFjC,
.wrapper-3JPufy button,
.accountBtnInner-sj5jLs,
.button-mM-y8i {
	background-color: rgba(var(--vtransparencycolor),var(--vtransparencyalpha)) !important;
}

.loading-17PYl_,
.partyMemberBackground-aSF9mc,
.friendsAction-__WNE9:not(:hover),
.button-mM-y8i:hover,
.guild-1EfMGQ:after {
	background-color: rgba(var(--vtransparencycolor),calc(var(--vtransparencyalpha) * 3)) !important;
}

.embed-IeVjo6,
.embedInner-1-fpTo {
	max-width: 100% !important;
}

.modal-3HD5ck,
.modal-3HD5ck .header-1R_AjF {
	box-shadow: 0 1px 0 0 rgba(var(--vtransparencycolor),.3), 0 1px 2px 0 rgba(var(--vtransparencycolor),.3) !important;
}
.modal-3HD5ck .footer-2yfCgX {
	box-shadow: inset 0 1px 0 rgba(var(--vtransparencycolor),.1) !important;
}
.modal-3HD5ck .header-1R_AjF + .inner-3wn6Q5,
.modal-3HD5ck .header-1R_AjF + .scrollerWrap-2lJEkd > .scroller-2FKFPG {
	padding-top: 10px;
}

.modal-3HD5ck .base-3dtUhz {
	border-radius: 0 !important;
}

.channels-Ie2l6A > div:nth-child(2) {
	border-radius: 5px 5px 0 0 !important;
}

.header-GwIGlr,
.changeDetails-bk98pu,
.member-3W1lQa .content-OzHfo4,
.channel-2QD9_O,
.wrapperHoveredCollapsed-1PADEo,
.wrapperHovered-28fu1D,
.userHovered-2_fT4Z {
	border-radius: 3px !important;
}

.container-16j22k:after,
.backdrop-1wrmKB:after {
	content: "";
	pointer-events: none !important;
	position: absolute;
	top: 22px;
	left: 0;
	width: 100%;
	height: 100%;
	background: rgba(var(--vtransparencycolor),calc(var(--vtransparencyalpha) * 2)) !important;
}
.container-16j22k .content-1-zrf2 {
	position: relative !important;
}
.container-16j22k .content-1-zrf2 ,
.container-16j22k .problems-3mgf6w {
	z-index: 100 !important;
}

.titleBar-AC4pGV:after {
	content: "";
	pointer-events: none !important;
	position: absolute;
	z-index: -1;
	top: 0;
	left: 0;
	width: 100%;
	height: 22px;
	background: rgba(var(--vtransparencycolor),calc((var(--vtransparencyalpha) * 3) + var(--vguildchanneltransparency))) !important;
}

.chat-3bRxxu form {
	box-shadow: 0 -1px 0 rgba(var(--vtransparencycolor),.3) !important;
}
.chat-3bRxxu form .channelTextArea-1LDbYG {
	position: relative !important;
	z-index: 20 !important;
}
.chat-3bRxxu form:after {
	content: "";
	pointer-events: none !important;
	position: absolute;
	z-index: 10;
	border-radius: 0 10px 0 0;
	top: 0;
	left: -20px;
	width: calc(100% + 40px);
	height: 100%;
	background: rgba(var(--vtransparencycolor),var(--vtransparencyalpha)) !important;
}

.footer-3oZnEF,
.image-3zK3Wt,
.image-1GzsFd,
.userSettingsSecurityImage-21pI_Q,
.emptyIconFriends-BrjhY9,
.empty-state-image,
.error-state .icon,
.errorStateIcon-p5L_DQ,
.emptyImage-1Y1gHr,
.imageError-2OefUi,
.image-3fVkBI,
.sad-discord,
.artwork-1vrmJ_,
img[src="/assets/bfffd518c76d3f6bc5e96eb52e4ae2cf.svg"],
.empty-placeholder .image,
.emptyPlaceholder-1zh-Eu .image-2JDb81 {
	opacity: 0.5 !important;
	pointer-events: none !important;
}
.footer-3oZnEF {
	background: url(https://discordapp.com/assets/72e1fd085e240aecf005e642e655c0f4.svg) no-repeat bottom !important;
}

.container-16j22k,
.appMount-3lHmkl,
.popout-2sKjHu,
.container-3gCOGc,
.friendsTable-133bsv,
.friendTableAddHeader-m9bzFr,
.tab-content > .standardSidebarView-3F1I7i,
.chat-3bRxxu,
.chat-3bRxxu .content-yTz4x3,
.chat-3bRxxu form,
.content-yTz4x3 .flex-spacer,
.embed-IeVjo6,
.media-engine-video,
.auditLog-3jNbM6,
.embedContainer-26S24y,
.assetWrapper-2Qw_5D,
.messagesWrapper-3lZDfY,
.container-1YxwTf code,
.typing-2GQL18,
.action-buttons,
.actionButtons-1sUUug,
.wrapper-2NJDcI,
.card-7JP0BX .body-SKIE6r,
.messageGroupWrapper-o-Zw7G,
.isLocalBot-38G0P0,
.article-3kb3qm,
.tileMedia-24cT6_,
.info-P9dFwH,
.mediaFade-1SdEfL,
.mediaFade-4Pqtcc,
.news-2KwXHF,
.description-3rB3Rp,
.autocomplete-header-background,
.tutorial-popout section,
.friend:not(:hover),
.container-3gCOGc .tabBar-1E2ExX .item-PXvHYJ,
.video-1FfuMD,
.category-2U57w6,
.incomingCallInner-2VmFiR,
.react-datepicker,
.container-PNkimc,
.headerBar-UHpsPw,
.titleBar-AC4pGV,
.titleWrapper-1l0xT9 .title-3qD0b-,
.searchResultsWrap-2DKFzt .searchResult-3pzFAB:before,
.searchResultsWrap-2DKFzt .searchResult-3pzFAB:after,
.searchResultsWrap-2DKFzt .channelName-1QajIf {
	background: transparent !important;
}

.guildsWrapper-5TJh6A,
.channels-Ie2l6A {
	background: rgba(var(--vtransparencycolor), var(--vguildchanneltransparency)) !important;
}

.members-1998pB {
	box-sizing: content-box !important;
	background: rgba(var(--vtransparencycolor), var(--vmemberlistransparency)) !important;
	padding: 0 !important;
}

.action-buttons,
.actionButtons-1sUUug,
.auditLog-3jNbM6,
.isLocalBot-38G0P0,
.row-2okwlC,
.bar-30k2ka,
.card-FDVird,
.searchResultsWrap-2DKFzt .searchResultMessage-2VxO12.hit-NLlWXA {
	box-shadow: none !important;
}

.popout-2sKjHu,
.announcingNitro-3Ptg6m,
.messageGroupWrapper-o-Zw7G,
.item-26Dhrx[style*="border-color: rgb(114, 137, 218)"],
.auditLog-3jNbM6,
.changeDetails-bk98pu,
.popout-2sKjHu,
.incomingCallInner-2VmFiR,
.date-picker,
.date-picker-hint,
.embedInner-1-fpTo,
.accountBtnInner-sj5jLs,
.callAvatarStatus-3y6S04,
.wrapper-3JPufy button,
.accountBtnInner-sj5jLs,
.searchResultsWrap-2DKFzt .searchResultMessage-2VxO12.expanded-v2Szsz,
.status-oxiHuE,
.iconBadge-2dji3k {
	border-color: transparent !important;
}

.edit-container-outer .avatar-large,
.divider-3gKybi + .divider-3gKybi,
.divider-3gKybi:before {
	visibility: hidden !important;
}

.bg-AYqtMd,
.autocomplete-arrow-wrapper {
	display: none !important;
}


/* ----------------------- COLORING ----------------------- */

.userSettingsSecurity-3IYeMF .isEnabled-24g9qA,
#app-mount :not(.searchLearnMore-3SQUAj) > .anchor-3Z-8Bb:not(.channelLink-2TxEu3):not(.guildsError-3cFMtY):not(.embedAuthorName-3mnTWj):not(.downloadButton-1bWXpg):not(.downloadLink-1ywL9o):not([style]),
#app-mount .usageInfo-2WQAwr,
#app-mount .genre-1Fi2SE,
#app-mount #bd-settings-sidebar a,
#app-mount .filenameLinkWrapper-1-14c5,
#app-mount .sampleLink-KPFu3I {
	color: rgb(var(--vaccentcolor)) !important;
}

.channels-Ie2l6A [class*="containerDrag"]:before,
.channels-Ie2l6A [class*="containerDrag"]:after,
.jumpToPresentBar-9P20AM,
.hasMore-3e72_v button,
.hasMore-sul95G button,
#bd-pub-button:hover,
.embedPill-1Zntps:not([style]),
.searchFilter-2ESiM3,
.searchAnswer-3Dz2-q,
.progressBar-3u8FBM,
.aka-1mqp34,
.item-26Dhrx[style*="background-color: rgb(114, 137, 218)"],
.valueChecked-m-4IJZ:not([style*="background-color: rgba(255, 255, 255, 0.3)"]),
.channel-2QD9_O.selected-1HYmZZ a,
.content-20Aix8:active,
.wrapperSelectedVoice-xzxa2u .content-20Aix8,
.wrapperSelectedText-3dSUjC .content-20Aix8,
.topPill-30KHOu .itemSelected-1qLhcL,
.itemSelected-1qLhcL:not(.tabBarItem-1b8RUP):not(.tabBarItem-1Cg-MI),
.selectableItem-1MP3MQ.selected-31soGA,
.round-2jCFai.checked-3_4uQ9[style*="background-color: rgb(67, 181, 129)"],
.root-SR8cQa .buttonInvertedDefault-1UdvTn {
	background: rgb(var(--vaccentcolor)) !important;
}
.button-2b6hmh:hover,
.button-2KyEfG:hover,
.wrapper-3JPufy button:hover,
.accountBtnInner-sj5jLs:hover,
.friendsAction-__WNE9:hover {
	background-color: rgb(var(--vaccentcolor)) !important;
}

.hasMore-3e72_v button,
.hasMore-sul95G button,
.round-2jCFai.checked-3_4uQ9[style*="border-color: rgb(67, 181, 129)"] {
	border-color: rgb(var(--vaccentcolor)) !important;
}

#app-mount .headerButtonColor-G7_f-V,
#app-mount .lookFilled-1Gx00P.hoverBrand-1_Fxlk.hasHover-3X1-zV:hover,
#app-mount .lookFilled-1Gx00P.hoverLink-i1fEKS.hasHover-3X1-zV:hover,
#app-mount .lookFilled-1Gx00P.colorBrand-3pXr91,
#app-mount .lookFilled-1Gx00P.colorLink-35jkBc,
#app-mount .root-SR8cQa > [class*="topSection"] .lookFilled-1Gx00P.colorGreen-29iAKY {
	background: rgb(var(--vaccentcolor)) !important;
}
#app-mount .lookGhost-2Fn_0-.colorBrand-3pXr91,
#app-mount .lookGhost-2Fn_0-.colorLink-35jkBc {
	color: rgb(var(--vaccentcolor)) !important;
	background: rgba(var(--vaccentcolor),0.1) !important;
}
#app-mount .lookOutlined-3sRXeN.colorBrand-3pXr91,
#app-mount .lookOutlined-3sRXeN.colorLink-35jkBc {
	color: rgb(var(--vaccentcolor)) !important;
	border-color: rgb(var(--vaccentcolor)) !important;
}
#app-mount .lookInverted-2D7oAl.colorBrand-3pXr91,
#app-mount .lookInverted-2D7oAl.colorLink-35jkBc {
	color: rgb(var(--vaccentcolor)) !important;
}
#app-mount .lookLink-9FtZy-.colorBrand-3pXr91 .contents-18-Yxp,
#app-mount .lookLink-9FtZy-.colorLink-35jkBc .contents-18-Yxp {
	color: rgb(var(--vaccentcolor)) !important;
}
#app-mount .lookLink-9FtZy-.colorBrand-3pXr91:active .contents-18-Yxp, 
#app-mount .lookLink-9FtZy-.colorBrand-3pXr91:hover .contents-18-Yxp,
#app-mount .lookLink-9FtZy-.colorLink-35jkBc:active .contents-18-Yxp, 
#app-mount .lookLink-9FtZy-.colorLink-35jkBc:hover .contents-18-Yxp {
	background-image: linear-gradient(0deg,transparent,transparent 1px,rgb(var(--vaccentcolor)) 0,rgb(var(--vaccentcolor)) 2px,transparent 0) !important;
}
#app-mount .lookFilled-1Gx00P.colorPrimary-3b3xI6 {
	background: rgb(var(--vaccentcolor)) !important;
}
#app-mount .lookGhost-2Fn_0-.colorPrimary-3b3xI6 {
	color: rgb(var(--vaccentcolor)) !important;
	background: rgba(var(--vaccentcolor),0.1) !important;
}
#app-mount .lookOutlined-3sRXeN.colorPrimary-3b3xI6 {
	color: rgb(var(--vaccentcolor)) !important;
	border-color: rgb(var(--vaccentcolor)) !important;
}
#app-mount .lookInverted-2D7oAl.colorPrimary-3b3xI6 {
	color: rgb(var(--vaccentcolor)) !important;
}
#app-mount .lookLink-9FtZy-.colorPrimary-3b3xI6 .contents-18-Yxp {
	color: rgb(var(--vaccentcolor)) !important;
}
#app-mount .lookLink-9FtZy-.colorPrimary-3b3xI6:active .contents-18-Yxp, 
#app-mount .lookLink-9FtZy-.colorPrimary-3b3xI6:hover .contents-18-Yxp {
	background-image: linear-gradient(0deg,transparent,transparent 1px,rgb(var(--vaccentcolor)) 0,rgb(var(--vaccentcolor)) 2px,transparent 0) !important;
}
#app-mount .lookOutlined-3sRXeN.colorRed-1TFJan {
	color: rgb(255,255,255) !important;
	background: rgb(240,71,71) !important;
	border: none !important;
}
#app-mount .lookOutlined-3sRXeN.colorBrand-3pXr91,
#app-mount .lookOutlined-3sRXeN.colorLink-35jkBc,
#app-mount .lookOutlined-3sRXeN.colorPrimary-3b3xI6 {
	background-color: transparent !important;
}
#app-mount .action-1lSjCi.join-33Tr-7 .actionButton-2PeQbJ {
	background-color: rgb(67,181,129) !important;
}

.nowPlaying-284llR {
	background: rgba(var(--vaccentcolor), calc(var(--vtransparencyalpha) * 3)) !important;
}

.guildIconExpired-2Qcq05 {
	background-color: rgba(47,49,54,.6) !important;
}

.standardSidebarView-3F1I7i .closeButton-1tv5uR:hover {
	background-color: rgba(var(--vaccentcolor), calc(var(--vtransparencyalpha) * 3)) !important;
}

.bottomLayer-XCk80b.hover-3nZwuJ:not(.green-1kY_LT) {
	fill: rgba(var(--vaccentcolor),0.5) !important;
}
.topLayer-1eMqbv.hover-3nZwuJ:not(.green-1kY_LT) {
	fill: rgb(var(--vaccentcolor)) !important;
}
.secondaryAccent-24W-RJ.hover-3nZwuJ:not(.green-1kY_LT) {
	fill: rgb(var(--vaccentcolor),0.8) !important;
}
.bottomLayer-XCk80b.hover-3nZwuJ.green-1kY_LT {
	fill: rgba(67,181,129,0.5) !important;
}
.topLayer-1eMqbv.hover-3nZwuJ.green-1kY_LT {
	fill: rgb(67,181,129) !important;
}
.secondaryAccent-24W-RJ.hover-3nZwuJ.green-1kY_LT {
	fill: rgb(67,181,129,0.8) !important;
}

.helpIcon-2EyVTp g {
	fill: #FFF !important;
}

.round-2jCFai.checked-3_4uQ9[style*="background-color: rgba(67, 181, 129, 0.14902)"] {
	background-color: rgba(var(--vaccentcolor), 0.14902) !important;
}
.round-2jCFai.checked-3_4uQ9[style*="border-color: rgba(67, 181, 129, 0.14902)"] {
	border-color: rgba(var(--vaccentcolor), 0.14902) !important;
}
.round-2jCFai.checked-3_4uQ9 polyline[stroke="#43b581"] {
	stroke: rgb(var(--vaccentcolor)) !important;
}

.search-bar {
	background: transparent !important;
	border: none !important;
}
.searchBarInner-1_Tg2R,
.search-bar-inner,
.searchBar-1MOL6S {
	border-radius: 5px !important;
	border: none !important;
	background: rgba(var(--vtransparencycolor),var(--vtransparencyalpha)) !important;
}
.search-bar input,
.searchBarInner-1_Tg2R input,
.searchBar-1MOL6S .input-3Xdcic {
	background: rgba(var(--vtransparencycolor),var(--vtransparencyalpha)) !important;
	border-radius: 3px !important;
	border-style: solid !important;
	border-width: 1px !important;
	color: rgb(255,255,255) !important;
	transition: background-color .15s ease,border .15s ease !important;
}
.search-bar input {
	margin-right: 15px !important;
}
.searchBar-1MOL6S .input-3Xdcic {
	margin-right: 3px !important;
}
.search-bar input:not(:focus),
.searchBarInner-1_Tg2R input:not(:focus),
.searchBar-1MOL6S .input-3Xdcic:not(:focus) {
	border-color: rgba(var(--vtransparencycolor),calc(var(--vtransparencyalpha) * 3)) !important;
}
.search-bar input:focus,
.searchBarInner-1_Tg2R input:focus,
.searchBar-1MOL6S .input-3Xdcic:focus {
	border-color: rgb(var(--vaccentcolor)) !important;
}
.privateChannels-1nO12o .search-bar .search-bar-inner input {
	margin-right: 0px !important;
	border: none !important;
}

.itemSelected-1qLhcL:not(.tabBarItem-1b8RUP):not(.tabBarItem-1Cg-MI),
.close-18n9bP,
.requirements-dEriwm,
.info-1Emy1X,
.footerMain-Z8i6ST,
.purchaseUnitOperatingSystem-cnbJPz,
.wrapperSelectedVoice-xzxa2u .wrapper-2NJDcI,
.Select-control,
.Select-value-label,
.Select-option,
.tutorial-popout .content p,
.input-cIJ7To,
.newMessagesBar-mujexs button,
#app-mount .hasMore-3e72_v button,
#app-mount .hasMore-sul95G button {
	opacity: 1 !important;
	color: rgb(255,255,255) !important;
}

.emptyState-N8MHmB,
.content-1zhNsr,
.content-3FEARf,
.requirementKey-14DT2D,
.icon-1IKq3C,
.textCell-1aBIUP,
.smallHeader-2h-9-U,
.label-13UUcd,
.footerSub-1Jedbi {
	color: rgb(200,200,200) !important;
}

.newMessagesBar-mujexs button:hover {
	text-decoration: underline;
}

#bd-pub-button,
.guildInner-3DSoA4 {
	transition: background 500ms ease !important;
}

.privateChannels-1nO12o .channel-2QD9_O .close-3hZ5Ni:not(:hover) {
	opacity: 0.2 !important;
}

.isMentioned-N-h9aa .wrapper-3WhCwL {
	background: transparent !important;
}
.isMentioned-N-h9aa:after {
	background: rgba(var(--vaccentcolor),0.2) !important;
	border-left-color: rgba(var(--vaccentcolor),0.8) !important;
}
.isMentioned-N-h9aa {
	background: rgba(var(--vaccentcolor),0.2) !important;
}

.bubble-3qRl2J,
.tooltip-1OS-Ti:not(.red-m6f4-H):not(.green-hbUqD5):not(.yellow-1oq44m):not(.tooltip-customcolor) {
	color: rgb(255,255,255) !important;
	background-color: rgb(var(--vaccentcolor)) !important;
}
.tooltip-1OS-Ti.right-KM_vfY:not(.red-m6f4-H):not(.green-hbUqD5):not(.yellow-1oq44m):not(.tooltip-customcolor):after {
	border-right-color: rgb(var(--vaccentcolor)) !important;
}
.bubble-3qRl2J:before,
.tooltip-1OS-Ti.top-1pTh1F:not(.red-m6f4-H):not(.green-hbUqD5):not(.yellow-1oq44m):not(.tooltip-customcolor):after {
	border-top-color: rgb(var(--vaccentcolor)) !important;
}
.tooltip-1OS-Ti.left-1wV7VO:not(.red-m6f4-H):not(.green-hbUqD5):not(.yellow-1oq44m):not(.tooltip-customcolor):after {
	border-left-color: rgb(var(--vaccentcolor)) !important;
}
.tooltip-1OS-Ti.bottom-19kp6S:not(.red-m6f4-H):not(.green-hbUqD5):not(.yellow-1oq44m):not(.tooltip-customcolor):after {
	border-bottom-color: rgb(var(--vaccentcolor)) !important;
}

.container-3nXdBP polyline[style*="stroke: slategray"],
.circular-2NaZOq circle {
	stroke: rgb(var(--vaccentcolor)) !important;
}
.background-yZEZik.path-3H_ZFA {
	stroke: rgba(var(--vtransparencycolor), calc(var(--vtransparencyalpha) * 3)) !important;
}
.selectorNitroText-3ZFWAe + svg path,
.container-3nXdBP polyline[style*="fill: slategray"] {
	fill: rgb(var(--vaccentcolor)) !important;
}

.guildsError-3cFMtY {
	background: rgba(240,71,71,calc(var(--vtransparencyalpha) * 3)) !important;
}

.unread-1xRYoj,
.mention-1f5kbO {
	background: rgba(240,71,71,calc(var(--vtransparencyalpha) * 6)) !important;
}

.itemDefault-3Jdr52[style*="background-color: rgb(240, 71, 71)"] {
	color: rgb(255,255,255) !important;
	background: rgb(240,71,71) !important;
	border: none !important;
}

.popout-3sVMXz .btn,
.private-channel-recipients-invite button,
.item-26Dhrx,
.valueChecked-m-4IJZ,
.bda-settings-button,
.bda-right button,
.friendsAction-__WNE9,
.unread-1xRYoj,
.mention-1f5kbO,
.questionMark-CWEQZn,
.jumpToPresentBar-9P20AM,
.newMessagesBar-mujexs,
.hasMore-3e72_v button,
.hasMore-sul95G button,
.wrapper-3JPufy button,
.accountBtnInner-sj5jLs,
.button-2b6hmh,
.button-2KyEfG,
.button-mM-y8i,
.button-38aScr {
	transition: all 100ms linear !important;
}
.announcingNitro-3Ptg6m:hover,
.popout-3sVMXz .btn:hover,
.friends-empty .btn:hover,
.private-channel-recipients-invite button:hover,
.valueChecked-m-4IJZ:hover,
.bda-settings-button:hover,
.bda-right button:hover,
.unread-1xRYoj:hover,
.mention-1f5kbO:hover,
.questionMark-CWEQZn:hover,
.jumpToPresentBar-9P20AM:hover,
.newMessagesBar-mujexs:hover,
.hasMore-3e72_v button:hover,
.hasMore-sul95G button:hover,
.btn-primary:hover,
.button-38aScr:hover {
	filter: brightness(150%) !important;
}

.bd-toast,
.toast {
	background-color: rgba(var(--vtransparencycolor), 0.9) !important;
	box-shadow: 0 0 0 1px rgba(var(--vtransparencycolor), 0.6), 0 2px 10px 0 rgba(0,0,0,.2) !important;
}
#app-mount .toast-brand,
#app-mount .noticeBrand-3nQBC_ {
	background-color: rgba(var(--vaccentcolor), 0.9) !important;
}
.toast-danger, 
.toast-error,
.noticeDanger-7u-yT9 {
	background-color: rgba(240, 71, 71, 0.9) !important;
}
.toast-default,
.noticeDefault-362Ko2 {
	background-color: rgba(242, 101, 34, 0.9) !important;
}
.toast-facebook,
.noticeFacebook-3equ5g {
	background-color: rgba(53, 80, 137, 0.9) !important;
}
.toast-info,
.noticeInfo-3_iTE1 {
	background-color: rgba(74, 144, 226, 0.9) !important;
}
.toast-premium,
.noticePremium-12Zvj9 {
	background-color: rgba(32, 34, 37, 0.9) !important;
}
.toast-spotify,
.noticeSpotify-27dhr0 {
	background-color: rgba(29, 185, 84, 0.9) !important;
}
.toast-streamermode,
.noticeStreamerMode-2TSQpg {
	background-color: rgba(89, 54, 149, 0.9) !important;
}
.toast-success,
.noticeSuccess-3Y62ob {
	background-color: rgba(67, 181, 129, 0.9) !important;
}
.toast-warning,
.toast-warn {
	background-color: rgba(255, 166, 0, 0.9) !important;
}


/* ----------------------- POPOUTS & MODALS ------------------------ */

.popout-3sVMXz {
	animation: none !important;
	overflow: visible !important;
	transform: none !important;
	box-shadow: none !important;
	pointer-events: none !important;
}
@keyframes popout-fadein {
	to {opacity: 1;}
}
.popout-3sVMXz > * {
	position: relative;
	opacity: 0 !important;
	animation: popout-fadein 100ms ease 200ms !important;
	animation-fill-mode: forwards !important;
	pointer-events: all !important;
}
.popout-3sVMXz[style*="translateX(-50%)"] > * {
	right: 50% !important;
}
.popout-3sVMXz[style*="translateX(-100%)"] > * {
	right: 100% !important;
}
.popout-3sVMXz[style*="translateX(-5"] > .container-3cGP6G {
	right: 50% !important;
}
.popout-3sVMXz.popout-googletranslate[style*="translateY(-100%)"] > * {
	position: relative !important;
	bottom: 422px !important;
}
.popout-3sVMXz[style*="translateY(-100%)"] > .everyonePopout-nEbJY3 {
	position: relative !important;
	bottom: 50vh !important;
}
.popout-3sVMXz[style*="translateY(-100%)"] > .container-3nXdBP {
	position: relative !important;
	bottom: 300px !important;
}
.popout-3sVMXz[style*="translateY(-100%)"] > .container-2x5lvQ {
	position: relative !important;
	bottom: 342px !important;
}
.popout-3sVMXz[style*="translateY(-100%)"] > .tutorial-popout {
	position: relative !important;
	bottom: 280px !important;
}
.popout-3sVMXz[style*="translateX(-"] > div[channel] {
	position: absolute !important;
	right: 0px !important;
}
.popout-3sVMXz[style*="translateX(-"] > .option-popout {
	position: absolute !important;
	right: 0px !important;
}
.popout-3sVMXz[style*="translateX(-11"] > .userPopout-3XzG_A {
	position: absolute !important;
	right: 20px !important;
}
.popout-3sVMXz[style*="translateY(-100%)"] > .userPopout-3XzG_A {
	position: absolute !important;
	bottom: -10px !important;
	left: 10px !important;
}
.popout-3sVMXz[style*="translateY(-100%)"] > .attachPopout-1n-ZKM {
	position: absolute !important;
	bottom: -15px !important;
	left: 3px !important;
}
.popout-3sVMXz[style*="translateX(-5"] > .regionSelectPopout-p9-0_W {
	position: absolute !important;
	right: -70px !important;
}
.popout-3sVMXz[style*="translateX(-6"] > .regionSelectPopout-p9-0_W {
	position: absolute !important;
	right: -50px !important;
}
.popout-3sVMXz .menu-Sp6bN1.alt-3btY0e {
	top: -235px !important;
}
.popout-3sVMXz[style*="translateX(-1"]:not([style*="translateX(-100%)"]) > #bda-qem,
.popout-3sVMXz[style*="translateX(-1"]:not([style*="translateX(-100%)"]) > .emojiPicker-3m1S-j,
.popout-3sVMXz[style*="translateX(-1"]:not([style*="translateX(-100%)"]) > #bda-qem-twitch-container,
.popout-3sVMXz[style*="translateX(-1"]:not([style*="translateX(-100%)"]) > #bda-qem-favourite-container {
	right: 340px !important;
}
.popout-3sVMXz[style*="translateY(-100%)"] > #bda-qem,
.popout-3sVMXz[style*="translateY(-100%)"] > .emojiPicker-3m1S-j,
.popout-3sVMXz[style*="translateY(-100%)"] > #bda-qem-twitch-container,
.popout-3sVMXz[style*="translateY(-100%)"] > #bda-qem-favourite-container {
	top: -350px !important;
}
.popout-3sVMXz[style*="transform: translateY(0%) translateX(-50%) translateZ(0px)"] > :first-child:not(#bda-qem) {
	right: 46% !important;
	top: -12px !important;
}
.attachPopout-1n-ZKM {
	padding: 0 !important;
}

.container-2x5lvQ .sparkline-3A-8OK {
	background-color: rgba(0,0,0,0.6);
	border-radius: 5px;
	padding: 5px;
}

#autocomplete-popout .autocomplete-scroller {
	height: 220px !important;
}

#permissions-modal {
	position: absolute !important;
}

.modal-1UGdnR .inner-1JeGVc > [class]:not(.premiumPaymentModal-3SpIbo):not(.container-3qKHyN):not(.detected-platform-accounts-modal):only-child {
	position: relative !important;
}
.modal-3Msmb3 .momentum-2CXCBH  .content-PS26MV > div > div[style*="transform: translateX"],
.modal-1UGdnR .inner-1JeGVc .form-77IDep .modalContent-hXHrpZ > div > div[style*="transform: translateX"],
.modal-1UGdnR .inner-1JeGVc .animator-US5i9g .item-5R5nmE {
	transform: none !important;
}
.modal-3Msmb3 .momentum-2CXCBH  .content-PS26MV > div > div[style*="transform: translateX"] + div[style*="transform: translateX"],
.modal-1UGdnR .inner-1JeGVc .form-77IDep .modalContent-hXHrpZ > div > div[style*="transform: translateX"] + div[style*="transform: translateX"],
.modal-1UGdnR .inner-1JeGVc .animator-US5i9g .item-5R5nmE + .item-5R5nmE {
	display: none !important;
}

.autocomplete-1vrmpx,
.contextMenu-HLZMGh,
.incomingCall-14zLcL,
.keyboardShortcutsModal-3piNz7,
.modal-1UGdnR .inner-1JeGVc > [class]:not(.premiumPaymentModal-3SpIbo):not(.container-3qKHyN):only-child,
.modal-3Msmb3,
.wrapper-2ZbzR9,
#permissions-modal,
.popout-2xBvMR,
.popout-3sVMXz > [class],
.popout-3sVMXz > [id],
.popoutList-T9CKZQ,
.quickswitcher-3JagVE,
.Select-menu-outer {
	transform: none !important;
	background: transparent !important;
	border-radius: 5px !important;
	border: none !important;
	box-shadow: none !important;
	overflow: visible !important;
}
.autocomplete-1vrmpx:after,
.autocomplete-1vrmpx:before,
.contextMenu-HLZMGh:after,
.contextMenu-HLZMGh:before,
.incomingCall-14zLcL:after,
.incomingCall-14zLcL:before,
.keyboardShortcutsModal-3piNz7:after,
.keyboardShortcutsModal-3piNz7:before,
.modal-1UGdnR .inner-1JeGVc > [class]:not(.premiumPaymentModal-3SpIbo):not(.container-3qKHyN):only-child:after,
.modal-1UGdnR .inner-1JeGVc > [class]:not(.premiumPaymentModal-3SpIbo):not(.container-3qKHyN):only-child:before,
.modal-3Msmb3:after,
.modal-3Msmb3:before,
.wrapper-2ZbzR9:after,
.wrapper-2ZbzR9:before,
#permissions-modal:after,
#permissions-modal:before,
.popout-2xBvMR:after,
.popout-2xBvMR:before,
.popout-3sVMXz > [class]:after,
.popout-3sVMXz > [class]:before,
.popout-3sVMXz > [id]:after,
.popout-3sVMXz > [id]:before,
.popoutList-T9CKZQ:after,
.popoutList-T9CKZQ:before,
.quickswitcher-3JagVE:after,
.quickswitcher-3JagVE:before,
.Select-menu-outer:after,
.Select-menu-outer:before {
	border-radius: 5px;
	content: "";
	position: absolute;
	z-index: -1;
	pointer-events: none;
}
.autocomplete-1vrmpx:after,
.contextMenu-HLZMGh:after,
.incomingCall-14zLcL:after,
.keyboardShortcutsModal-3piNz7:after,
.modal-1UGdnR .inner-1JeGVc > [class]:not(.premiumPaymentModal-3SpIbo):not(.container-3qKHyN):only-child:after,
.modal-3Msmb3:after,
.wrapper-2ZbzR9:after,
#permissions-modal:after,
.popout-2xBvMR:after,
.popout-3sVMXz > [class]:after,
.popout-3sVMXz > [id]:after,
.popoutList-T9CKZQ:after,
.quickswitcher-3JagVE:after,
.Select-menu-outer:after {
	top: 0;
	bottom: 0;
	right: 0;
	left: 0;
	background: rgba(var(--vtransparencycolor),calc(var(--vtransparencyalpha) * 3));
}
.autocomplete-1vrmpx:before,
.contextMenu-HLZMGh:before,
.incomingCall-14zLcL:before,
.keyboardShortcutsModal-3piNz7:before,
.modal-1UGdnR .inner-1JeGVc > [class]:not(.premiumPaymentModal-3SpIbo):not(.container-3qKHyN):only-child:before,
.modal-3Msmb3:before,
.wrapper-2ZbzR9:before,
#permissions-modal:before,
.popout-2xBvMR:before,
.popout-3sVMXz > [class]:before,
.popout-3sVMXz > [id]:before,
.popoutList-T9CKZQ:before,
.quickswitcher-3JagVE:before,
.Select-menu-outer:before {
	top: -1px;
	bottom: -1px;
	right: -1px;
	left: -1px;
	background: var(--vbackground) center/cover;
	filter: blur(var(--vpopoutblur));
	background-attachment: fixed;
}
/* fix for double shading in guild create modal */
.modal-1UGdnR .inner-1JeGVc > [class]:not(.premiumPaymentModal-3SpIbo):not(.container-3qKHyN):only-child .wrapper-2ZbzR9:before,
.modal-1UGdnR .inner-1JeGVc > [class]:not(.premiumPaymentModal-3SpIbo):not(.container-3qKHyN):only-child .wrapper-2ZbzR9:after {
	display: none !important;
}

.header-39GIC8 {
	background: transparent !important;
}
.header-39GIC8 > * {
	position: relative !important;
}
.header-39GIC8:after,
.header-39GIC8:before {
	content: "";
	position: absolute;
	z-index: -1;
	pointer-events: none;
	top: 0;
	bottom: 0;
	right: 0;
	left: 0;
}
.header-39GIC8:after {
	background: rgba(var(--vtransparencycolor),calc(var(--vtransparencyalpha) * 3));
}
.header-39GIC8:before {
	background: var(--vbackground) center/cover;
	filter: blur(var(--vpopoutblur));
	background-attachment: fixed;
}

.uploadDropModal-2kTwbc {
	border-radius: 5px !important;
}

.Select-menu-outer.inChat {
	top: -200px !important;
}

.keyboardShortcutsModal-3piNz7 .modalTitle-37O4n6,
.keyboardShortcutsModal-3piNz7 .modalSubtitle-1Pj5nv {
	margin: 0 !important;
	border: none !important;
	background: rgba(var(--vtransparencycolor),calc(var(--vtransparencyalpha) * 3)) !important;
	position: relative !important;
}
.keyboardShortcutsModal-3piNz7 .modalTitle-37O4n6 .content-2Add9f,
.keyboardShortcutsModal-3piNz7 .modalSubtitle-1Pj5nv {
	color: hsla(0,0%,100%,.8) !important;
}
.keyboardShortcutsModal-3piNz7 .modalTitle-37O4n6 {
	padding: 20px 40px 5px 40px !important;
}
.keyboardShortcutsModal-3piNz7 .keybindDescription-2RDbC2 {
	color: hsla(0,0%,100%,.8) !important;
}

.incomingCall-14zLcL {
	transform: none !important;
	top: calc(50vh - 146px) !important;
	left: calc(50vw - 109px) !important;
}

.autocomplete-1vrmpx:after {
	background: rgba(var(--vtransparencycolor),calc(var(--vtransparencyalpha) * 4));
}

.phoneVerificationModal-OzcDc3 .phoneField-38N1bJ {
	background: rgba(var(--vtransparencycolor),calc(var(--vtransparencyalpha) * 3)) !important;
}
.phoneVerificationModal-OzcDc3 .phoneField-38N1bJ .countryButton-3xq3Ts{
	background: rgba(66,66,66,0.3) !important;
}
.phoneVerificationModal-OzcDc3 .phoneField-38N1bJ .inputField-aNPXsv {
	background: transparent !important;
}
.phoneVerificationModal-OzcDc3 .phoneFieldPopout-h7c9mt {
	z-index: 100 !important;
}
.phoneVerificationModal-OzcDc3 .phoneFieldScroller-2IJUdK {
	border-radius: 5px !important;
	background: rgba(var(--vtransparencycolor),calc(var(--vtransparencyalpha) * 3)) !important;
	padding: 0 !important;
	margin-bottom: 10px !important;
}

.uploadArea-3QgLtW:before {
	content: "";
	background: rgba(var(--vtransparencycolor),calc(var(--vtransparencyalpha) * 3));
	position: absolute;
	width: 100%;
	height: 100%;
	left: 0;
	z-index: -1;
	pointer-events: none;
}

#bda-qem {
	padding: 0 !important;
	border: none !important;
}
#bda-qem > button {
	border: none !important;
	box-shadow: none !important;
	color: hsla(0,0%,100%,.8) !important;
}
#bda-qem > button:not(.active) {
	background: rgba(var(--vtransparencycolor),calc(var(--vtransparencyalpha) * 4)) !important;
}
#bda-qem > button.active {
	background: rgba(var(--vtransparencycolor),var(--vtransparencyalpha)) !important;
}
.emojiPicker-3m1S-j .header-1nkwgG {
	background: rgba(var(--vtransparencycolor),var(--vtransparencyalpha)) !important;
}
.emojiPicker-3m1S-j .dimmer-3iH-5D.visible-3k45bQ {
	background: rgba(var(--vtransparencycolor),0.6) !important;
}
.emojiPicker-3m1S-j .popout-2nUePc {
	border-color: rgb(var(--vaccentcolor)) !important;
	background: rgba(var(--vtransparencycolor),0.8) !important;
}
.emojiPicker-3m1S-j .popout-2nUePc .item-16cXuq:hover {
	background-color: rgba(var(--vaccentcolor),0.6) !important;
}
.emojiPicker-3m1S-j .stickyHeader-1SS0JU {
	background: rgba(var(--vaccentcolor),0.8) !important;
	border-radius: 0 0 5px 5px !important;
}
.emojiPicker-3m1S-j .category-2U57w6 {
	color: rgb(255,255,255) !important;
}
#bda-qem-favourite-container .emote-container:hover,
#bda-qem-twitch-container .emote-container:hover,
.emojiPicker-3m1S-j .emojiItem-109bjA:hover,
.emojiPicker-3m1S-j .emojiItem-109bjA.selected-39BZ4S {
	background-color: rgba(var(--vtransparencycolor),calc(var(--vtransparencyalpha) * 3)) !important;
}
.emojiPicker-3m1S-j .categories-1feg4n {
	border: none !important;
	margin: 0 !important;
	padding: 0 12px !important;
	background-color: rgba(var(--vtransparencycolor),calc(var(--vtransparencyalpha) * 3)) !important;
}

.regionSelectModal-12e-57 .regionSelectModalOption-2DSIZ3 {
	background: rgba(var(--vtransparencycolor),calc(var(--vtransparencyalpha) * 3)) !important;
	border-color: rgba(var(--vtransparencycolor),calc(var(--vtransparencyalpha) * 6)) !important;
}
.regionSelectModal-12e-57 .regionSelectModalOption-2DSIZ3:hover {
	background: rgba(var(--vtransparencycolor),calc(var(--vtransparencyalpha) * 2)) !important;
	border-color: rgba(var(--vaccentcolor),calc(var(--vtransparencyalpha) * 6)) !important;
}

.overlay-n52Tzn,
.gamePreview-9weYR2 .background-3zYSQO {
	-webkit-mask: linear-gradient(rgb(var(--vtransparencycolor)),transparent) !important;
}
.tileMedia-24cT6_ {
	-webkit-mask: linear-gradient(rgb(var(--vtransparencycolor)) 50%, transparent) !important;
}
.tileMedia-1q3guD .tileMedia-24cT6_ {
	height: 300px !important;
}

.userPopout-3XzG_A .footer-1fjuF6 {
	border-radius: 0 0 5px 5px !important;
	background: rgba(var(--vtransparencycolor),calc(var(--vtransparencyalpha) * 3)) !important;
}
.userPopout-3XzG_A .body-3iLsc4 {
	background: rgba(var(--vtransparencycolor),calc(var(--vtransparencyalpha) * 2)) !important;
	margin: 10px !important;
	border-radius: 5px !important;
}
.userPopout-3XzG_A .body-3iLsc4 textarea:focus {
	background: rgba(var(--vtransparencycolor),calc(var(--vtransparencyalpha) * 3)) !important;
}
.userPopout-3XzG_A .body-3iLsc4 .bodyTitle-Y0qMQz {
	color: hsla(0,0%,100%,.8) !important;
} 
.userPopout-3XzG_A .quickMessage-1yeL4E {
	background: rgba(var(--vtransparencycolor),var(--vtransparencyalpha)) !important;
	border-radius: 3px !important;
	border-style: solid !important;
	border-width: 1px !important;
	color: rgb(255,255,255) !important;
	margin-right: 15px !important;
	transition: background-color .15s ease,border .15s ease !important;
}
.userPopout-3XzG_A .quickMessage-1yeL4E:not(:focus) {
	border-color: rgba(var(--vtransparencycolor),calc(var(--vtransparencyalpha) * 3)) !important;
}
.userPopout-3XzG_A .quickMessage-1yeL4E:focus {
	border-color: rgb(var(--vaccentcolor)) !important;
}
.root-SR8cQa .topSectionNormal-2-vo2m,
.userPopout-3XzG_A .headerNormal-T_seeN {
	border-radius: 5px 5px 0 0 !important;
	background: rgba(var(--vtransparencycolor),calc(var(--vtransparencyalpha) * 3)) !important;
	border-bottom: 1px solid rgba(var(--vtransparencycolor),var(--vtransparencyalpha)) !important;
}
.root-SR8cQa .topSectionNormal-2-vo2m .tabBarContainer-1s1u-z {
	border-color: rgba(var(--vtransparencycolor),var(--vtransparencyalpha)) !important;
}
.root-SR8cQa .topSectionPlaying-1J5E4n,
.userPopout-3XzG_A .headerPlaying-j0WQBV {
	border-radius: 5px 5px 0 0 !important;
	background: rgba(var(--vaccentcolor),var(--vtransparencyalpha)) !important;
	border-bottom: 1px solid rgba(var(--vaccentcolor),var(--vtransparencyalpha)) !important;
}
.root-SR8cQa .topSectionPlaying-1J5E4n .tabBarContainer-1s1u-z {
	border-color: rgba(var(--vaccentcolor),var(--vtransparencyalpha)) !important;
}
.root-SR8cQa .topSectionSpotify-1lI0-P,
.userPopout-3XzG_A .headerSpotify-zpWxgT {
	border-radius: 5px 5px 0 0 !important;
	background: rgba(67,181,129,var(--vtransparencyalpha)) !important;
	border-bottom: 1px solid rgba(67,181,129,var(--vtransparencyalpha)) !important;
}
.root-SR8cQa .topSectionSpotify-1lI0-P .tabBarContainer-1s1u-z {
	border-color: rgba(67,181,129,var(--vtransparencyalpha)) !important;
}
.root-SR8cQa .topSectionStreaming-1Tpf5X,
.userPopout-3XzG_A .headerStreaming-2FjmGz {
	border-radius: 5px 5px 0 0 !important;
	background: rgba(89,54,149,var(--vtransparencyalpha)) !important;
	border-bottom: 1px solid rgba(89,54,149,var(--vtransparencyalpha)) !important;
}
.root-SR8cQa .topSectionStreaming-1Tpf5X .tabBarContainer-1s1u-z {
	border-color: rgba(89,54,149,var(--vtransparencyalpha)) !important;
}
.root-SR8cQa .topSectionXbox-3fWLjS,
.userPopout-3XzG_A .headerXbox-3G-4PF {
	border-radius: 5px 5px 0 0 !important;
	background: rgba(16,126,16,var(--vtransparencyalpha)) !important;
	border-bottom: 1px solid rgba(16,126,16,var(--vtransparencyalpha)) !important;
}
.root-SR8cQa .topSectionXbox-3fWLjS .tabBarContainer-1s1u-z {
	border-color: rgba(16,126,16,var(--vtransparencyalpha)) !important;
}
.root-SR8cQa .userInfoSection-2acyCx {
	border-color: rgba(var(--vtransparencycolor),calc(var(--vtransparencyalpha) * 2)) !important;	
}
.root-SR8cQa .body-3ND3kc {
	border-radius: 0 0 5px 5px !important;
	background: rgba(var(--vtransparencycolor),var(--vtransparencyalpha)) !important;
}
.root-SR8cQa .userInfoSectionHeader-CBvMDh {
	color: rgb(255,255,255) !important;
}
.root-SR8cQa .body-3ND3kc textarea:focus {
	background: rgba(var(--vtransparencycolor),calc(var(--vtransparencyalpha) * 3)) !important;
}
.root-SR8cQa .listRow-hutiT_:hover {
	background: linear-gradient(90deg,rgba(var(--vtransparencycolor),0.3) 90%,rgba(var(--vtransparencycolor),0));
}
.root-SR8cQa .connectedAccount-36nQx7 {
	border: none !important;	
	background: rgba(var(--vtransparencycolor),calc(var(--vtransparencyalpha) * 3)) !important;
}
.root-SR8cQa .connectedAccountOpenIcon-2cNbq5:hover {
	filter: brightness(200%);
}

.private-channel-recipients-invite .search-bar {
	background: transparent !important;
}
.private-channel-recipients-invite .search-bar-inner {
	border-radius: 5px !important;
	background: rgba(var(--vtransparencycolor),var(--vtransparencyalpha)) !important;
	padding: 0 !important;
}
.private-channel-recipients-invite .search-bar input {
	background: rgba(var(--vtransparencycolor),var(--vtransparencyalpha)) !important;
	border-radius: 3px !important;
	border-style: solid !important;
	border-width: 1px !important;
	color: rgb(255,255,255) !important;
	transition: background-color .15s ease,border .15s ease !important;
}
.private-channel-recipients-invite .search-bar input:not(:focus) {
	border-color: rgba(var(--vtransparencycolor),calc(var(--vtransparencyalpha) * 3)) !important;
}
.private-channel-recipients-invite .search-bar input:focus {
	border-color: rgb(var(--vaccentcolor)) !important;
}

.option-1mJRMP,
.Select-option {
	top: 0 !important;
	background: rgba(var(--vtransparencycolor),var(--vtransparencyalpha)) !important;
}

.container-3cGP6G {
	padding: 0 !important;
}

.item-2J1YMK {
	margin: 0 !important;
	color: rgb(255,255,255) !important;
	width: 100% !important;
	padding: 2px 4px !important;
	border-radius: 0 !important;
}

.item-2yFVoY,
.item-2J1YMK,
.attachPopoutRow-KrE-f6,
.item-1GzJrl,
.option-1mJRMP:not(.optionActive-KkAdqq):hover,
.Select-option:hover {
	background: rgba(var(--vtransparencycolor),calc(var(--vtransparencyalpha) * 2)) !important;
}
.item-2yFVoY:hover,
.item-2J1YMK:hover,
.attachPopoutRow-KrE-f6:hover,
.item-1GzJrl:hover,
.optionActive-KkAdqq,
.Select-option.is-selected {
	background: rgba(var(--vtransparencycolor),calc(var(--vtransparencyalpha) * 4)) !important;
}

.queryContainer-RKFJW-,
.searchQuery-1B7rtx {
	border: none !important;
	background: rgba(var(--vtransparencycolor),calc(var(--vtransparencyalpha) * 2)) !important;
}
.searchQuery-1B7rtx.selected-rZcOL- {
	background: rgba(var(--vtransparencycolor),calc(var(--vtransparencyalpha) * 2)) !important;
}
.queryContainer-RKFJW-.focused-2bY0OD {
	background: rgba(var(--vtransparencycolor),calc(var(--vtransparencyalpha) * 3)) !important;
}
.resultsGroup-r_nuzN {
	background: rgba(var(--vtransparencycolor),var(--vtransparencyalpha)) !important;
	padding-top: 0 !important;
}
.resultsGroup-r_nuzN:before {
	display: none !important;
}
.resultsGroup-r_nuzN .option-96V44q.selected-rZcOL- {
	background: rgba(var(--vtransparencycolor),calc(var(--vtransparencyalpha) * 2)) !important;
}
.resultsGroup-r_nuzN .option-96V44q:after {
	display: none !important;
}
.resultsGroup-r_nuzN .option-96V44q.selected-rZcOL-:before {
	background-color: rgb(var(--vaccentcolor)) !important;
	border-radius: 3px !important;
	width: 34px !important;
}
.resultsGroup-r_nuzN .header-2N-gMV, 
.resultsGroup-r_nuzN .plusIcon-v0BTrL, 
.resultsGroup-r_nuzN .searchClearHistory-2cSSMO, 
.resultsGroup-r_nuzN .searchLearnMore-3SQUAj .anchor-3Z-8Bb {
	color: rgb(255,255,255) !important;
}
.resultsGroup-r_nuzN .header-2N-gMV {
	padding: 8px 20px !important;
}
.resultsGroup-r_nuzN .searchClearHistory-2cSSMO, 
.resultsGroup-r_nuzN .searchLearnMore-3SQUAj {
	top: 4px !important;
}
.option-96V44q strong,
.option-96V44q .answer-1n6g43,
.option-96V44q .displayedNick-3xxvzU {
	color: #caccce !important;
}
.option-96V44q .searchResultChannelIcon-1DnTme,
.option-96V44q .searchResultChannelCategory-1l0lSn,
.option-96V44q .filter-3Y_im-,
.option-96V44q .displayUsername-Qekxml,
.option-96V44q .nonText-3CRkO0 {
	color: #a0a0a0 !important;
}

.datePicker--XZbmJ .react-datepicker__day:not(.react-datepicker__day--outside-month) {
	border-color: rgba(var(--vtransparencycolor),calc(var(--vtransparencyalpha) * 3)) !important;
}
.datePicker--XZbmJ .react-datepicker__day--outside-month {
	border-color: transparent !important;
	background: rgba(var(--vtransparencycolor),calc(var(--vtransparencyalpha) * 3)) !important;
}
.datePicker--XZbmJ .react-datepicker__header,
.datePicker--XZbmJ .react-datepicker__month-container,
.datePicker--XZbmJ .react-datepicker__day--disabled:not(.react-datepicker__day--outside-month) {
	background: rgba(var(--vtransparencycolor),var(--vtransparencyalpha)) !important;
}
.datePicker--XZbmJ .react-datepicker__header {
	padding-bottom: 5px !important;
}
.datePicker--XZbmJ .react-datepicker__navigation {
	top: 30px !important;
}
.datePicker--XZbmJ .react-datepicker__navigation--previous {
	left: 30px !important;
}
.datePicker--XZbmJ .react-datepicker__navigation--next {
	right: 30px !important;
}
.datePicker--XZbmJ .react-datepicker__current-month {
	padding: 10px 0 !important;
}
.datePicker--XZbmJ .react-datepicker__current-month,
.datePicker--XZbmJ .react-datepicker__day-name,
.datePicker--XZbmJ .react-datepicker__day:not(.react-datepicker__day--disabled):hover,
.datePicker--XZbmJ .react-datepicker__day:not(.react-datepicker__day--disabled):not(.react-datepicker__day--outside-month),
.datePicker--XZbmJ .datePickerHint-3Q1Udw .hint-165cR4,
.datePicker--XZbmJ .datePickerHint-3Q1Udw .hintValue-29ny8Z {
	color: rgb(255,255,255) !important;
}
.datePicker--XZbmJ .react-datepicker__day--disabled:not(.react-datepicker__day--outside-month) {
	color: #888 !important;
}
.datePicker--XZbmJ .react-datepicker__day--outside-month {
	color: #333 !important;
}
.datePicker--XZbmJ .datePickerHint-3Q1Udw {
	margin: 0 !important;
	padding: 20px !important;
	display: flex !important;
	justify-content: center !important;
}

.contextMenu-HLZMGh > .item-1Yvehc.disabled-2xniQf:hover,
.contextMenu-HLZMGh > .item-1Yvehc,
.itemGroup-1tL0uz {
	background-color: rgba(var(--vtransparencycolor),calc(var(--vtransparencyalpha) * 2)) !important;
}
.item-1Yvehc {
	background-color: transparent !important;
	position: relative !important;
	margin: 0 !important;
	padding: 8px 9px !important;
	border-radius: 0px !important;
}
.item-1GzJrl:not(.invite-271nFU):not(.leave-1DRJfn),
.item-1Yvehc:not(.danger-2dXSTE):not(.disabled-2xniQf):not([style*="color:"]),
.item-1Yvehc:not(.danger-2dXSTE):not(.disabled-2xniQf):hover {
	color: rgb(255,255,255) !important;
}
.item-1Yvehc:not(.disabled-2xniQf):hover {
	background-color: rgba(var(--vaccentcolor),calc(var(--vtransparencyalpha) * 8)) !important;
	border-radius: 5px !important;
}
.item-1GzJrl.invite-271nFU:hover {
	color: rgb(255,255,255) !important;
	background-color: rgba(var(--vaccentcolor),calc(var(--vtransparencyalpha) * 6)) !important;
}
.item-1Yvehc.danger-2dXSTE:hover,
.item-1GzJrl.leave-1DRJfn:hover {
	color: rgb(255,255,255) !important;
	background-color: rgba(240,71,71,calc(var(--vtransparencyalpha) * 6)) !important;
}
.item-1GzJrl:hover .icon-2doZ3q,
.item-1GzJrl:not(.invite-271nFU):not(.leave-1DRJfn) .icon-2doZ3q {
	filter: brightness(1000%);
}
.item-1GzJrl.leave-1DRJfn .icon-2doZ3q[style*="/assets/00de6b3cbb5c4dbcec817c91262f5f5b.svg"] {
	background: rgb(240, 71, 71) !important;
	-webkit-mask: url('data:image/svg+xml; utf8, <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18"><g fill="none" fill-rule="evenodd"><path d="M0 0h18v18H0z"></path><path fill="#737F8D" d="M14.25 2.25H3.75c-.8325 0-1.5.6675-1.5 1.5v3h1.5v-3h10.5v10.5H3.75v-3h-1.5v3c0 .8284271.67157287 1.5 1.5 1.5h10.5c.8284271 0 1.5-.6715729 1.5-1.5V3.75c0-.8325-.675-1.5-1.5-1.5zm-6.69 9.435l1.065 1.065L12.375 9l-3.75-3.75L7.56 6.3075 9.5025 8.25H2.25v1.5h7.2525L7.56 11.685z"></path></g></svg>') center/cover no-repeat;
}
.separator-2zcjq8 {
	border-bottom-color: rgba(255,255,255,0.4);
}

.uploadModal-2ifh8j .footer-3mqk7D {
	border-radius: 0 0 5px 5px;
	background: rgba(var(--vtransparencycolor),calc(var(--vtransparencyalpha) * 3)) !important;
}
.uploadModal-2ifh8j .innerEnabled-3g80kR {
	background: rgba(var(--vtransparencycolor),calc(var(--vtransparencyalpha) * 3)) !important;
}


.resultFocused-3aIoYe {
	background: rgba(var(--vtransparencycolor),calc(var(--vtransparencyalpha) * 3)) !important;
}
.quickswitcher-3JagVE .input-2VB9rf {
	background: rgba(var(--vtransparencycolor),var(--vtransparencyalpha)) !important;
	border-radius: 3px !important;
	border-style: solid !important;
	border-width: 1px !important;
	box-shadow: none !important;
	box-sizing: border-box !important;
	color: rgb(255,255,255) !important;
	font-size: 16px !important;
	height: 40px !important;
	margin: 5px 8px !important;
	outline: none !important;
	padding: 10px !important;
	transition: background-color .15s ease,border .15s ease !important;
}
.quickswitcher-3JagVE .input-2VB9rf:not(:focus) {
	border-color: rgba(var(--vtransparencycolor),calc(var(--vtransparencyalpha) * 3)) !important;
}
.quickswitcher-3JagVE .input-2VB9rf:focus {
	border-color: rgb(var(--vaccentcolor)) !important;
}

.tipsWithResults-HhTE9b {
	border-color: rgba(var(--vtransparencycolor),calc(var(--vtransparencyalpha) * 3)) !important;
}

.tipsListNav-2AYmjC,
.tipsMiscControls-vCHjy1 {
	color: hsla(0,0%,100%,.8) !important;
}

.wrapper-O5i5-0,
.wrapper-O5i5-0 > * {
	height: 450px !important;
	display: flex !important;
	flex-direction: column !important;
}
.wrapper-O5i5-0 .form-inner {
	flex: 1 1 auto;
}
.instantInviteModal-3vhcvC .form-header,
.instantInviteModalAdvanced-3qJETM .form-actions,
.instantInviteModal-3vhcvC .form-actions {
	border-color: transparent !important;
	background: rgba(var(--vtransparencycolor),calc(var(--vtransparencyalpha) * 3)) !important;
}
.instantInviteModal-3vhcvC .clipboardInputInner-1EXMA3 {
	background: rgba(var(--vtransparencycolor),var(--vtransparencyalpha)) !important;
	border-color: rgba(var(--vtransparencycolor),calc(var(--vtransparencyalpha) * 3)) !important;
	border-radius: 3px !important;
	border-style: solid !important;
	border-width: 1px !important;
}
.instantInviteModal-3vhcvC .clipboardInput-3LfnPL input {
	background: rgba(var(--vtransparencycolor),var(--vtransparencyalpha)) !important;
	color: rgb(var(--vaccentcolor)) !important;
}
.instantInviteModal-3vhcvC .clipboardInput-3LfnPL button {
	border: none !important;
	background: rgb(var(--vaccentcolor)) !important;
}
.instantInviteModal-3vhcvC .clipboardInput-3LfnPL button:before {
	background: linear-gradient(90deg,hsla(0,0%,100%,0),rgba(var(--vtransparencycolor),.5)) !important;
}
.instantInviteModal-3vhcvC header,
.instantInviteModal-3vhcvC .blurb-zsamaY,
.instantInviteModal-3vhcvC .expireText-34b09Y,
.instantInviteModal-3vhcvC .checkbox span,
.instantInviteModalAdvanced-3qJETM .checkbox span,
.instantInviteModalAdvanced-3qJETM .help-text,
.instantInviteModalAdvanced-3qJETM .control-group label,
.instantInviteModalAdvanced-3qJETM .form-actions .btn-default {
	color: hsla(0,0%,100%,.8) !important;
}
.instantInviteModalAdvanced-3qJETM .control-group label {
	height: 20px !important;
}
.instantInviteModalAdvanced-3qJETM .form-actions {
	padding: 10px 60px !important;
}
.instantInviteModalAdvanced-3qJETM .form-actions .btn-default:not(:hover) {
	border: none !important;
}
.instantInviteModal-3vhcvC,
.instantInviteModalAdvanced-3qJETM,
.instantInviteModal-3vhcvC .form-header {
	box-shadow: 0 1px 0 0 rgba(var(--vtransparencycolor),.3), 0 1px 2px 0 rgba(var(--vtransparencycolor),.3) !important;
}
.instantInviteModal-3vhcvC .form-actions,
.instantInviteModalAdvanced-3qJETM .form-actions {
	box-shadow: inset 0 1px 0 rgba(var(--vtransparencycolor),.1) !important;
}

.premiumPaymentModal-3SpIbo .lookInverted-2D7oAl.colorBrand-3pXr91 {
	color: rgb(114,137,218) !important;
}


/* ----------------------- ICONS ----------------------- */

.userSettingsSecurity-3IYeMF {
	position: relative !important;
}
.userSettingsSecurity-3IYeMF .isEnabled-24g9qA .lockIcon-2Hj8Tq {
	visibility: hidden !important;
}
.userSettingsSecurity-3IYeMF .isEnabled-24g9qA:before {
	content: "";
	position: absolute;
	margin-top: 2px;
	width: 10px;
	height: 14px;
	-webkit-mask: url('data:image/svg+xml; utf8, <svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" width="10px" height="14px" viewBox="0 0 10 14" version="1.1"><g xmlns="http://www.w3.org/2000/svg" stroke="none" stroke-width="1" fill="none" fill-rule="evenodd"><g fill="#43B581"><path d="M 8,6 L 2,6 L 2,5 C 2,3.346 3.346,2 5,2 C 6.654,2 8,3.346 8,5 L 8,6 Z M 4,12 L 6,12 L 6,8 L 4,8 L 4,12 Z M 5,0 C 2.238,0 0,2.238 0,5 L 0,6 L 0,10 L 0,12 C 0,13.104 0.896,14 2,14 L 8,14 C 9.104,14 10,13.104 10,12 L 10,10 L 10,6 L 10,5 C 10,2.238 7.762,0 5,0 L 5,0 Z"></path></g></g></svg>') center/cover no-repeat !important;
	background: rgb(var(--vaccentcolor)) !important;
}

.icon-2Po-VO[style*="/assets/b8029fe196b8f1382e90bbe81dab50dc.svg"] {
	-webkit-mask: url('data:image/svg+xml; utf8, <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18"><g fill="none" fill-rule="evenodd"><path d="M18 0H0v18h18z"/><path fill="#43B581" d="M0 8h14.2l-3.6-3.6L12 3l6 6-6 6-1.4-1.4 3.6-3.6H0"/></g></svg>') center/cover no-repeat !important;
	background: rgb(var(--vaccentcolor)) !important;
	width: 18px;
}
.icon-2Po-VO[style*="/assets/c30220457097b064286a8759a9b6c4af.svg"] {
	-webkit-mask: url('data:image/svg+xml; utf8, <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18"><path xmlns="http://www.w3.org/2000/svg" fill="#43B581" fill-rule="evenodd" d="M17.7163041 15.36645368c-.0190957.02699568-1.9039523 2.6680735-2.9957762 2.63320406-3.0676659-.09785935-6.6733809-3.07188394-9.15694343-5.548738C3.08002193 9.9740657.09772497 6.3791404 0 3.3061316v-.024746C0 2.2060575 2.61386252.3152347 2.64082114.2972376c.7110335-.4971705 1.4917101-.3149497 1.80959713.1372281.19320342.2744561 2.19712724 3.2811005 2.42290565 3.6489167.09884826.1608492.14714912.3554431.14714912.5702838 0 .2744561-.07975258.5770327-.23701117.8751101-.1527655.2902036-.65262318 1.1664385-.89862055 1.594995.2673396.3768148.94804468 1.26429792 2.351016 2.66357424 1.39173858 1.39027775 2.28923588 2.07641807 2.67002628 2.34187563.4302146-.2452108 1.3086162-.74238132 1.5972981-.89423205.5447887-.28682915 1.0907006-.31944893 1.4568885-.08661115.3459689.2182151 3.3383754 2.21027167 3.6225641 2.41611376.2695862.19234426.4144887.5399137.4144887.91672846 0 .2969525-.089862.61190215-.2808189.88523346"/></svg>') center/cover no-repeat !important;
	background: rgb(var(--vaccentcolor)) !important;
}


/* ----------------------- EXTRAS ----------------------- */

/* fix flashing whe nopening and closing settings */
.layer-3QrUeG:first-child {
	will-change: unset !important;
	opacity: unset !important;
	transform: unset !important;
	transition: unset !important;
	animation: unset !important;
}
.layer-3QrUeG.stop-animations:first-child[style*="opacity"] {
	opacity: 0 !important;
}

/* custom css container */
#bd-customcss-editor {
	background-color: rgba(var(--vtransparencycolor),.5) !important;
}
#bd-customcss-attach-controls {
	background-color: rgba(var(--vtransparencycolor),.8) !important;
	box-shadow: none !important;
}
#bd-customcss-editor .ace_selection {
	background-color: rgb(var(--vaccentcolor)) !important;
}
#bd-customcss-editor .ace_selected-word {
	border-color: rgb(var(--vaccentcolor)) !important;
}
#bd-customcss-editor .ace_gutter {
	color: #DDD !important;
	background-color: rgba(var(--vtransparencycolor),.3) !important;
}
#bd-customcss-editor .ace_active-line {
	background-color: rgba(var(--vaccentcolor),.5) !important;
}
#bd-customcss-editor .ace_gutter-active-line {
	background-color: rgba(var(--vaccentcolor),.7) !important;
}

/* roles */
.role-2irmRk {
	border-radius: 5px !important;
	padding: 0 5px !important;
	position: relative !important;
}
.role-2irmRk .roleName-32vpEy {
	color: rgb(255,255,255) !important;
	margin: 0 !important;
	font-weight: normal !important;
	position: relative !important;
	height: 20px !important;
	line-height: 20px !important;
	z-index: 1000 !important;
	pointer-events: none !important;
}
.role-2irmRk .roleCircle-3xAZ1j {
	position: absolute !important;
	border-radius: 3px !important;
	opacity: 0.3 !important;
	height: 100% !important;
	width: 100% !important;
	left: 0 !important;
	top: 0 !important;
}
.role-2irmRk .roleCircleButton-377y0l:hover {
	opacity: 1 !important;
	z-index: 2000 !important;
}

/* ownertag */
.ownerIcon-uZ6mE7 {
	margin: 0px 5px 0 7px !important;
	background: white !important;
	height: 10px !important;
	width: 38px !important;
	overflow: visible !important;
}
.ownerIcon-uZ6mE7 path {
	d: path('M -38.15 24.225 c -1.675 -0.625 -3.075 -1.875 -3.975 -3.5 l -0.75 -1.35 0 -13.5 0 -13.5 0.6 -1.125 c 0.8 -1.525 1.9 -2.675 3.4 -3.45 l 1.25 -0.675 46.625 0 46.625 0 1.125 0.6 c 1.525 0.8 2.675 1.9 3.45 3.4 l 0.675 1.25 0 13.5 0 13.5 -0.675 1.25 c -0.775 1.5 -1.925 2.6 -3.45 3.4 l -1.125 0.6 -46.25 0.05 c -45.375 0.05 -46.275 0.05 -47.525 -0.45 z m 15.675 -10.125 c 2.725 -1.55 4.1 -4.325 4.075 -8.225 -0.05 -3.75 -1.45 -6.375 -4.2 -7.825 -1.125 -0.6 -1.55 -0.675 -3.675 -0.675 -2.175 0 -2.525 0.075 -3.85 0.75 -2.8 1.425 -4.25 4.225 -4.225 8.125 0.05 4.275 1.85 7.125 5.325 8.425 0.575 0.2 1.675 0.3 3.05 0.25 1.825 -0.075 2.325 -0.175 3.5 -0.825 z m 15.875 -5.575 c 1.025 -3.375 1.9 -6.175 1.975 -6.225 0.05 -0.05 0.2 0.325 0.35 0.85 0.15 0.55 1 3.325 1.875 6.225 l 1.6 5.25 1.575 0 1.575 0 2.45 -8.5 c 1.325 -4.675 2.45 -8.525 2.45 -8.55 0 -0.05 -0.725 -0.075 -1.625 -0.075 l -1.6 0 -0.225 0.85 c -0.15 0.475 -0.85 3.175 -1.575 6 -0.725 2.85 -1.375 5.075 -1.475 4.975 -0.125 -0.15 -2.6 -8.325 -3.45 -11.4 -0.1 -0.375 -0.35 -0.425 -1.75 -0.375 l -1.65 0.075 -1.75 5.95 c -0.95 3.25 -1.825 5.85 -1.9 5.75 -0.1 -0.125 -0.825 -2.725 -1.6 -5.825 -0.8 -3.1 -1.525 -5.725 -1.625 -5.825 -0.225 -0.225 -2.525 0.025 -3.025 0.325 -0.2 0.125 0.3 2.275 2 8.15 1.25 4.375 2.325 8.125 2.375 8.3 0.075 0.225 0.575 0.3 1.65 0.25 l 1.55 -0.075 1.825 -6.1 z m 19.35 0.3 c 0 -5.075 0.05 -5.875 0.35 -5.575 0.175 0.2 2.05 2.875 4.15 5.95 l 3.775 5.55 1.375 0 1.35 0 0 -8.625 0 -8.625 -1.5 0 -1.5 0 -0.05 5.675 -0.075 5.675 -3.875 -5.675 -3.875 -5.675 -1.55 0 -1.575 0 0 8.625 0 8.625 1.5 0 1.5 0 0 -5.925 z m 24.75 4.55 l 0 -1.35 -3.425 -0.075 -3.45 -0.075 -0.075 -2.3 -0.075 -2.325 2.9 0 2.9 0 -0.175 -1.175 c -0.075 -0.675 -0.225 -1.275 -0.325 -1.375 -0.075 -0.1 -1.275 -0.225 -2.65 -0.25 l -2.5 -0.075 0 -2 0 -2 3.325 -0.075 3.3 -0.075 0 -1.35 0 -1.375 -4.875 0 -4.875 0 0 8.625 0 8.625 5 0 5 0 0 -1.375 z m 6.25 -2.025 l 0 -3.375 0.7 0.075 c 0.55 0.05 1.05 0.625 2.925 3.4 l 2.25 3.35 1.375 -0.175 c 0.75 -0.1 1.5 -0.25 1.675 -0.325 0.175 -0.125 -0.5 -1.3 -1.95 -3.375 -1.225 -1.775 -2.225 -3.25 -2.225 -3.3 0 -0.05 0.475 -0.35 1.075 -0.7 1.475 -0.875 2.175 -2.2 2.175 -4.15 0 -3.925 -2.05 -5.275 -8.05 -5.275 l -3.2 0 0 8.625 0 8.625 1.625 0 1.625 0 0 -3.4 z M -28.375 11.9 c -1.725 -0.75 -2.725 -2.875 -2.725 -5.8 0 -1.75 0.1 -2.225 0.75 -3.5 0.4 -0.8 1.025 -1.675 1.425 -1.95 0.95 -0.7 3.55 -0.85 4.65 -0.3 3.55 1.85 3.575 9.675 0.05 11.525 -0.9 0.45 -3.125 0.475 -4.15 0.025 z M 43.625 5.45 c -0.075 -0.2 -0.1 -1.475 -0.075 -2.85 l 0.075 -2.475 1.575 0.025 c 1.8 0.025 2.7 0.425 3.2 1.4 0.7 1.35 0.275 2.975 -1 3.625 -1.075 0.55 -3.6 0.75 -3.775 0.275 z');
	fill: rgb(var(--vaccentcolor)) !important;
}
.ownerIcon-uZ6mE7:hover,
.owner-help-icon:hover {
	filter: brightness(150%) !important;
}
.owner-help-icon {
	padding: 1px 0 !important;
	opacity: 1 !important;
	background-image: none !important;
	width: 42px !important;
}
.owner-help-icon:after {
	background: rgb(var(--vaccentcolor));
	border-radius: 3px;
	color: rgb(255,255,255);
	content: "OWNER";
	font-size: 10px;
	font-weight: 500;
	height: 14px;
	left: 0;
	line-height: 15px;
	padding: 1px 3px;
	top: 0;
	text-transform: uppercase;
	vertical-align: bottom;
}

/* selection */ 
::selection {
	background: rgb(var(--vaccentcolor)) !important;
}

/* scrollbars */ 
::-webkit-scrollbar {
	width: 10px !important;
	height: 10px !important;
}
::-webkit-scrollbar,
::-webkit-scrollbar-track,
::-webkit-scrollbar-track-piece {
	border-color: transparent !important;
	background: transparent !important;
}
::-webkit-scrollbar-thumb {
	border-radius: 10px !important;
	border: 1px solid rgba(var(--vaccentcolor),.3) !important;
	background-clip: content-box !important;
	background-color: rgba(var(--vtransparencycolor),calc(var(--vtransparencyalpha) * 3)) !important;
}
::-webkit-scrollbar-corner {
	visibility: hidden !important;
}

/* change member loadings screen */
.memberGroupsPlaceholder-3mwPub, .placeholderAvatar-damqh6, .placeholderUsername-2B_OA9 {
	background-color: rgb(var(--vaccentcolor)) !important;
}

/* fix BTTV tooltips */
.tipsy {
	opacity: 1 !important;
}
.tipsy div {
	border-radius: 5px;
	background-color: rgb(var(--vaccentcolor)) !important;
	padding: 5px; 
}

/* fix span flickering */
html, span:not(.spinner-item) {
	backface-visibility: hidden;
}

/* friendsadd input */
.wrapper-1cBijl {
	border: none !important;
	background: transparent !important;
}
.addFriendHint-3Y70FX {
	font-size: 16px !important;
	height: 40px !important;
	outline: none !important;
	padding: 0 10px !important;
}
.addFriendInput-4bcerK {
	background: rgba(var(--vtransparencycolor),var(--vtransparencyalpha)) !important;
	border-radius: 3px !important;
	border-style: solid !important;
	border-width: 1px !important;
	box-shadow: none !important;
	box-sizing: border-box !important;
	color: rgb(255,255,255) !important;
	font-size: 16px !important;
	height: 40px !important;
	outline: none !important;
	padding: 10px !important;
	transition: background-color .15s ease,border .15s ease !important;
}
.addFriendInput-4bcerK:not(:focus) {
	border-color: rgba(var(--vtransparencycolor),calc(var(--vtransparencyalpha) * 3)) !important;
}
.addFriendInput-4bcerK:focus {
	border-color: rgb(var(--vaccentcolor)) !important;
}

/* fix public servers page */
#pubslayer {
	background: var(--vbackground) center/cover !important;
	opacity: 1 !important;
	animation: none !important;
} 
#pubslayer {
	z-index: 1000 !important;
}
#pubslayer > .standardSidebarView-3F1I7i {
	background: rgba(var(--vtransparencycolor),calc(var(--vtransparencyalpha) * 3)) !important;
}
#pubslayer button,
.bd-server-card.bd-server-card-pinned:after {
	background: rgb(var(--vaccentcolor)) !important;
}
#pubslayer input {
	background: rgba(var(--vtransparencycolor),var(--vtransparencyalpha)) !important;
	border-radius: 3px !important;
	border-style: solid !important;
	border-width: 1px !important;
	box-shadow: none !important;
	box-sizing: border-box !important;
	transition: background-color .15s ease,border .15s ease !important;
}
#pubslayer input:not(:focus) {
	border-color: rgba(var(--vtransparencycolor),calc(var(--vtransparencyalpha) * 3)) !important;
}
#pubslayer input:focus {
	border-color: rgb(var(--vaccentcolor)) !important;
}

/* group dm name change */
.input-autosize-input {
	box-sizing: border-box !important;
	border-radius: 3px !important;
	transition: background-color .15s ease,border .15s ease !important;
}
.input-autosize-input:focus {
	background: rgba(var(--vtransparencycolor),var(--vtransparencyalpha)) !important;
	border: 1px solid rgb(var(--vaccentcolor)) !important;
}


/* ----------------------- OLDCLASSES ----------------------- */

/* fix twitch and favorite menu */
#bda-qem-twitch-container .scroller-wrap,
#bda-qem-favourite-container .scroller-wrap {
	overflow: hidden;
	-ms-flex: 1 1 auto;
	-webkit-box-flex: 1;
	display: -webkit-box;
	display: -ms-flexbox;
	display: flex;
	flex: 1 1 auto;
	height: 100%;
	position: relative;
}
#bda-qem-twitch-container .scroller-wrap .scroller,
#bda-qem-favourite-container .scroller-wrap .scroller {
	-webkit-box-flex: 1;
	flex: 1 1 auto;
	overflow-y: scroll;
	overflow-x: hidden;
}

/* fix help modal */ 
.need-help-modal,
.need-help-modal .header {
	box-shadow: 0 1px 0 0 rgba(var(--vtransparencycolor),.3), 0 1px 2px 0 rgba(var(--vtransparencycolor),.3) !important;
}
.need-help-modal .footer {
	box-shadow: inset 0 1px 0 rgba(var(--vtransparencycolor),.1) !important;
}
#help-query {
	background: rgba(var(--vtransparencycolor),var(--vtransparencyalpha)) !important;
	border-radius: 3px !important;
	border-style: solid !important;
	border-width: 1px !important;
	box-shadow: none !important;
	box-sizing: border-box !important;
	color: rgb(255,255,255) !important;
	font-size: 16px !important;
	height: 40px !important;
	margin: 5px 20px !important;
	outline: none !important;
	padding: 10px !important;
	transition: background-color .15s ease,border .15s ease !important;
}
#help-query:not(:focus) {
	border-color: rgba(var(--vtransparencycolor),calc(var(--vtransparencyalpha) * 3)) !important;
}
#help-query:focus {
	border-color: rgb(var(--vaccentcolor)) !important;
}


/* ----------------------- PLUGINSUPPORT ----------------------- */

/* MemberCount */
#MemberCount:after,
#MemberCount:before {
	content: "";
	position: absolute;
	top: 0;
	bottom: 0;
	right: 0;
	left: 0;
	z-index: -1;
	pointer-events: none;
}
#MemberCount:after {
	background: rgba(var(--vtransparencycolor),calc((var(--vtransparencyalpha) * 3.1) + var(--vmemberlistransparency) * 0.6));
}
#MemberCount:before {
	background: var(--vbackground) center/cover;
	filter: blur(var(--vbackgroundblur));
	background-attachment: fixed;
}

/* oldtitlebar */
.hidden-by-OTB .bd-modal-close-area:after,
.hidden-by-OTB .container-16j22k:after,
.hidden-by-OTB .backdrop-1wrmKB:after {
	top: 0 !important;
}
.hidden-by-OTB .splashBackground-1FRCko:before {
	display: none !important;
}
.wrapper-3Q5DdO .settingsTitlebarOTB {
	color: white;
}

/* statuseverywhere */
.status-oxiHuE.typing-1KJk_j {
	border-radius: 999px !important;
}

/* displayserveraschannels */
.DSAC-styled .guildSeparator-1X4GQ1 ~ .guild-1EfMGQ.selected-ML3OIq {
	background-color: rgb(var(--vaccentcolor)) !important;
}
.DSAC-styled .guildSeparator-1X4GQ1 ~ .guild-1EfMGQ:not(.selected-ML3OIq):hover {
	opacity: 1 !important;
	background-color: rgba(var(--vtransparencycolor),calc(var(--vtransparencyalpha) * 3)) !important;
}

/* betterformattingredux */
.bf-toolbar {
	background: transparent !important;
	top: -50px !important;
	transform: none !important;
}
.bf-toolbar:after {	
	content: "";
	display: block;
	width: 100%;
	height: calc(100% - 15px);
	position: absolute;	
	z-index: 200;
	pointer-events: none;
	left: 0px;
	top: 5px;
	border-radius: 3px;
	background: rgba(var(--vtransparencycolor),calc(var(--vtransparencyalpha) * 5));
	transform: translate(0,55px);
	transition: all 200ms ease;
}
.bf-toolbar.bf-visible:after,
.bf-toolbar.bf-hover:hover:after {
	transform: translate(0,0px);
	transition: all 200ms cubic-bezier(0,0,0,1);
}
.uploadModal-2ifh8j .bf-toolbar:after {
	display: none !important;
}
.uploadModal-2ifh8j .bf-toolbar:after,
.container-1YxwTf .bf-toolbar:after {
	transform: translate(0,0) !important;
}
.bf-toolbar:before {
	border-radius: 4px !important;
	z-index: 100 !important;
	background: var(--vbackground) center/cover !important;
	filter: blur(var(--vpopoutblur)) !important;
	background-attachment: fixed !important;
}
.bf-toolbar > * {
	z-index: 300 !important;
}
.bf-toolbar .format:hover {
	background-color: rgb(var(--vaccentcolor)) !important
}
.uploadModal-2ifh8j .bf-toolbar {
	top: 10px !important;
}

/***** FIX UNTIL CLASSCHANGE ******/

.uploadModal-2ifh8j .bf-toolbar {
	position: relative;
	transform: none;
	padding: 5px 0;
	margin-right: 0;
	border-radius: 2px;
	text-align: center;
	background: #424549;
}
.uploadModal-2ifh8j .bf-toolbar:before {
	display: none;
}
.uploadModal-2ifh8j .bf-toolbar .format,
.uploadModal-2ifh8j .bf-toolbar:before,
.container-1YxwTf .bf-toolbar .format,
.container-1YxwTf .bf-toolbar:before {
	transform: translate(0,0);
}
.uploadModal-2ifh8j .bf-toolbar .bf-arrow,
.container-1YxwTf .bf-toolbar .bf-arrow {
	display: none;
}
.container-1YxwTf .bf-toolbar {
	padding: 10px 5px 15px 5px;
	animation: slide-up 300ms cubic-bezier(0,0,0,1), opacity 300ms ease;
}

/* serverfolders */ 
.guildIcon-CT-ZDq {
	position: static !important;
}

/* citador & replyer */
.quote-msg .avatar-large {
	left: 0 !important;
}
.quote-msg .avatar-large:hover:after {
	color: rgb(255,255,255) !important;
	background-color: rgb(var(--vaccentcolor)) !important;
	border: none !important;
	width: 15px !important;
	height: 15px !important;
	left: 26px !important;
	text-align: center !important;
	line-height: 15px !important;
}
.citar-btn {
	background-color: transparent! important;
	background-size: contain !important;
	font-size:0 !important;
	position: relative;
	top: -4px !important;
	padding: 8px 10px !important;
	filter: drop-shadow(0 0 2px black);
	opacity: 0.7 !important;
}
.replyer-icon {
	position: relative !important;
	padding: 0 3px 1px 3px !important;
	margin-top: 1px !important;
}
.replyer[style*="cursor:pointer;color:rgba(255,255,255,.4) !important;position:relative;top:-1px;"] {
	background: url(data:image/svg+xml;base64,PHN2ZyBmaWxsPSIjRkZGRkZGIiBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4gICAgPHBhdGggZD0iTTEwIDlWNWwtNyA3IDcgN3YtNC4xYzUgMCA4LjUgMS42IDExIDUuMS0xLTUtNC0xMC0xMS0xMXoiLz4gICAgPHBhdGggZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIvPjwvc3ZnPg==) no-repeat center center !important;
	background-size: contain !important;
	font-size:0 !important;
	top: -5px !important;
	margin-left:10px !important;
	padding: 8px 10px !important;
	filter: drop-shadow(0 0 2px rgb(var(--vtransparencycolor)));
	opacity: 0.7 !important;
}
.citar-btn:hover,
.replyer-icon:hover,
.replyer[style*="cursor:pointer;color:rgba(255,255,255,.4) !important;position:relative;top:-1px;"]:hover {
	border-radius: 3px;
	opacity: 1 !important; 
	background-color: rgba(var(--vtransparencycolor),calc(var(--vtransparencyalpha) * 2)) !important
}
.citar-btn:active,
.replyer-icon:active,
.replyer[style*="cursor:pointer;color:rgba(255,255,255,.4) !important;position:relative;top:-1px;"]:active {
	background-color: rgb(var(--vaccentcolor)) !important
}

/* direct download */
#files_directDownload .file {
	background-color: rgba(var(--vtransparencycolor),0.4) !important;
	border-color: rgba(var(--vaccentcolor),0.2) !important;
	border-radius: 6px 6px 0 0 !important;
}
#files_directDownload .file svg {
	fill: #FFF !important;
	opacity: 0.5 !important;
}
#files_directDownload .file svg:hover {
	opacity: 1 !important;
}
#files_directDownload .file span {
	color: rgb(255,255,255) !important;
}
#files_directDownload .file .progress-bar {
	background-color: rgb(var(--vaccentcolor)) !important
}

/* dateviewer */
#dv-mount {
	background: rgba(var(--vtransparencycolor), var(--vmemberlistransparency)) !important;
}

/* permissionviewer */
#permissions-modal {
	position: absolute !important;
}
#permissions-modal .header {
	box-shadow: 0 1px 0 0 rgba(var(--vtransparencycolor),.3), 0 1px 2px 0 rgba(var(--vtransparencycolor),.3) !important;
}
#permissions-modal .modal-body {
	background: transparent !important;
	box-shadow: none !important;
}
#permissions-modal .role-side {
	background: rgba(var(--vtransparencycolor),calc(var(--vtransparencyalpha) * 2)) !important;
}
#permissions-modal .perm-side {
	background: rgba(var(--vtransparencycolor),var(--vtransparencyalpha)) !important;
}
#permissions-modal .role-item.selected {
	background: rgba(var(--vtransparencycolor),calc(var(--vtransparencyalpha) * 3)) !important;
}
#permissions-modal .role-item:hover {
	background: rgba(var(--vtransparencycolor),var(--vtransparencyalpha)) !important;
}


/* ----------------------- BDv2 MENU ----------------------- */

.bd-badge-outer {
	display: none !important;
}
.bd-autocomplete,
.bd-modal-inner {
	transform: none !important;
	background: transparent !important;
	border-radius: 5px !important;
	border: none !important;
	box-shadow: none !important;
	overflow: visible !important;
	position: absolute !important
}
.bd-autocomplete:after,
.bd-autocomplete:before,
.bd-modal-inner:after,
.bd-modal-inner:before {
	border-radius: 5px;
	content: "";
	position: absolute;
	z-index: -1;
	pointer-events: none;
}
.bd-autocomplete:after,
.bd-modal-inner:after {
	top: 0;
	bottom: 0;
	right: 0;
	left: 0;
	background: rgba(var(--vtransparencycolor),calc(var(--vtransparencyalpha) * 3));
}
.bd-autocomplete:before,
.bd-modal-inner:before {
	top: -1px;
	bottom: -1px;
	right: -1px;
	left: -1px;
	background: var(--vbackground) center/cover;
	filter: blur(var(--vpopoutblur));
	background-attachment: fixed;
}
.bd-modal-inner {
	max-height: 80% !important;
}
.bd-modal-body .tab-bar-item.selected {
	color: rgb(var(--vaccentcolor)) !important;
}
.bd-modal header {
	border-color: transparent !important;
	background: rgba(var(--vtransparencycolor),calc(var(--vtransparencyalpha) * 3)) !important;
}
.bd-modal-body {
	background: transparent !important;
}
.bd-modal .footer button {
	background: rgb(var(--vaccentcolor)) !important;
	transition: all 100ms linear !important;
}
.bd-autocomplete-selector {
	background: transparent !important;
}
.bd-autocomplete-selector:hover {
	background: rgba(var(--vtransparencycolor),calc(var(--vtransparencyalpha) * 3));
}
.bd-modal-close-area {
	background: var(--vbackdrop) center/cover !important;
	filter: blur(var(--vbackdrop)) !important;
	opacity: 1 !important;
	animation: none !important;
}
.bd-modal-close-area:after {
	content: "";
	pointer-events: none !important;
	position: absolute;
	top: 22px;
	left: 0;
	width: 100%;
	height: 100%;
	background: rgba(var(--vtransparencycolor),calc(var(--vtransparencyalpha) * 2)) !important;
}
.bd-sidebar-region,
.bd-content-region {
	background: var(--vbackground) center/cover !important;
	filter: blur(var(--vbackgroundblur)) !important;
	background-attachment: fixed !important;
}
.bd-sidebar-region .bd-settingswrap,
.bd-info {
	margin: 0 !important;
	background: rgba(var(--vtransparencycolor),calc(var(--vtransparencyalpha) * 4)) center/cover !important;
}
.bd-info {
	padding-bottom: 20px !important;
}
.bd-content {
	background: rgba(var(--vtransparencycolor),calc(var(--vtransparencyalpha) * 3)) center/cover !important;
}
.bd-card {
	background: rgba(var(--vtransparencycolor),calc(var(--vtransparencyalpha) * 3)) center/cover !important;
	border-radius: 10px !important;
	padding: 5px !important;
}
.bd-modal-titlelink,
.bd-content-author-link:hover,
.bd-settingswrap-header-text {
	color: rgb(var(--vaccentcolor)) !important;
}
.bd-tooltip {
	color: rgb(255,255,255) !important;
}
.bd-header,
.bd-vtext,
.bd-tabbar .bd-button:not(.bd-active) {
	color: rgb(200,200,200) !important;
}
.vc-input__label,
.bd-settings-scheme-hint,
.bd-hint,
.bd-card-extra {
	color: rgb(170,170,170) !important;
}
.bd-material-button .bd-material-design-icon {
	fill: rgb(200,200,200) !important;
}
.bd-modal [stroke="#3e82e5"], .bd-settings [stroke="#3e82e5"] {
	stroke: rgb(var(--vaccentcolor)) !important;
}
.bd-settings-x:hover {
	background-color: rgba(var(--vaccentcolor),calc(var(--vtransparencyalpha) * 3)) !important;
}
.bd-sidebar .bd-item:hover {
	background: rgba(var(--vtransparencycolor),calc(var(--vtransparencyalpha) * 3)) !important;
}
.bd-footer-alert {
	background: rgba(var(--vtransparencycolor),0.8) !important;
}
.bd-slider-bar {
	padding: 1px !important;
}
.bd-guilds .bd-guild.bd-active,
.bd-guilds .bd-guild:hover {
	background-color: rgb(var(--vaccentcolor)) !important;
}
.bd-guilds .bd-guild.bd-active {
	box-shadow: 0 0 7px 2px rgb(var(--vaccentcolor)) !important;
}
.bd-tooltip,
.bd-slider-bar-filled,
.bd-radio.bd-radio-selected,
.bd-material-button:hover,
.bd-switch-wrapper .bd-switch.bd-checked,
.bd-sidebar .bd-item.active,
:not(.bd-tabbar):not(.bd-active) > .bd-button:not(.bd-err):not(.bd-tp):not(.bd-ok) {
	background: rgb(var(--vaccentcolor)) !important;
}
.bd-tooltip-arrow {
	border-top-color: rgb(var(--vaccentcolor)) !important;
}
.bd-radio.bd-radio-selected,
.bd-form-textinput input[type="text"]:focus, 
.bd-form-textinput input[type="number"]:focus, 
.bd-form-numberinput input[type="text"]:focus, 
.bd-form-numberinput input[type="number"]:focus,
.bd-settings-scheme.bd-active .bd-settings-scheme-icon,
.bd-tabbar .bd-button:hover, 
.bd-tabbar .bd-button.bd-active {
	border-color: rgb(var(--vaccentcolor)) !important;
}
.bd-tabbar .bd-button:not(.bd-active) {
	border-color: rgb(200,200,200) !important;
}

.bd-button:hover {
	filter: brightness(150%) !important;
}
.bd-button {
	transition: all 100ms linear !important;
}
.bd-button-group .bd-button {
	border: none !important;
}
.bd-button-group .bd-button:not(:last-of-type) {
	margin: 0 1px 0 0 !important;
}
.bd-dropdown-current,
.bd-dropdown-text,
.bd-dropdown-option {
	color: rgb(255,255,255) !important;
}
.bd-dropdown-current {
	background: rgba(var(--vtransparencycolor),var(--vtransparencyalpha)) !important;
	border-color: rgba(var(--vtransparencycolor),calc(var(--vtransparencyalpha) * 3)) !important;
}
.bd-dropdown-current:hover {
	border-color: rgba(var(--vtransparencycolor),calc(var(--vtransparencyalpha) * 6)) !important;
}
.bd-dropdown-option {
	top: 0 !important;
	background: rgba(var(--vtransparencycolor),var(--vtransparencyalpha)) !important;
}
.bd-dropdown-option.is-selected {
	background: rgba(var(--vtransparencycolor),calc(var(--vtransparencyalpha) * 4)) !important;
}
.bd-dropdown-option:hover {
	background: rgba(var(--vtransparencycolor),calc(var(--vtransparencyalpha) * 2)) !important;
	border-color: rgba(var(--vtransparencycolor),calc(var(--vtransparencyalpha) * 6)) !important;
}
.bd-dropdown-options {
	transform: none !important;
	background: transparent !important;
	border-radius: 5px !important;
	border: none !important;
	box-shadow: none !important;
	overflow: visible !important;
}
.bd-dropdown-options:after,
.bd-dropdown-options:before {
	border-radius: 5px;
	content: "";
	position: absolute;
	z-index: -1;
	pointer-events: none;
}
.bd-dropdown-options:after{
	top: 0;
	bottom: 0;
	right: 0;
	left: 0;
	background: rgba(var(--vtransparencycolor),calc(var(--vtransparencyalpha) * 3));
}
.bd-dropdown-options:before {
	top: -1px;
	bottom: -1px;
	right: -1px;
	left: -1px;
	background: var(--vbackground) center/cover;
	filter: blur(var(--vpopoutblur));
	background-attachment: fixed;
}
.vc-chrome-toggle-icon-highlight,
.bd-modal-x:hover {
	border-color: transparent !important;
	background: rgba(var(--vtransparencycolor),calc(var(--vtransparencyalpha) * 3)) !important;
}
.vc-chrome-body {
	background: transparent !important;
}
.vc-chrome-body:after,
.vc-chrome-body:before {
	content: "";
	position: absolute;
	z-index: -1;
	pointer-events: none;
}
.vc-chrome-body:after {
	top: 0;
	bottom: 0;
	right: 0;
	left: 0;
	background: rgba(var(--vtransparencycolor),calc(var(--vtransparencyalpha) * 3));
}
.vc-chrome-body:before {
	top: -1px;
	bottom: -1px;
	right: -1px;
	left: -1px;
	background: var(--vbackground) center/cover;
	filter: blur(var(--vpopoutblur));
	background-attachment: fixed;
}
.vc-input__input {
	background: rgba(var(--vtransparencycolor),var(--vtransparencyalpha)) !important;
	border-radius: 3px !important;
	border-style: solid !important;
	border-width: 1px !important;
	box-shadow: none !important;
	transition: background-color .15s ease,border .15s ease !important;
}
.vc-input__input:not(:focus) {
	border-color: rgba(var(--vtransparencycolor),calc(var(--vtransparencyalpha) * 3))
}
.vc-input__input:focus {
	border-color: rgb(var(--vaccentcolor)) !important;
}


/* ----------------------- COPYRIGHT PROTECTION ----------------------- */

html > head + body > div#app-mount.appMount-3lHmkl > div.typeWindows-1za-n7.titleBar-AC4pGV.horizontalReverse-3tRjY7.flex-1O1GKY.directionRowReverse-m8IjIq.justifyStart-2NDFzi.alignStretch-DpGPf3 > div.wordmark-2iDDfm {
	display: block !important;
	position: absolute !important;
	width: 55px !important;
	height: 16px !important;
	margin: 0 !important;
	padding: 4px 8px 3px !important;
	top: 0 !important;
	left: 0 !important;
	bottom: unset !important;
	right: unset !important;
	opacity: 0.6 !important;
	visibility: visible !important;
}
html > head + body > div#app-mount.appMount-3lHmkl > div.typeWindows-1za-n7.titleBar-AC4pGV.horizontalReverse-3tRjY7.flex-1O1GKY.directionRowReverse-m8IjIq.justifyStart-2NDFzi.alignStretch-DpGPf3 > div.wordmark-2iDDfm:after {
	content: url('data:image/svg+xml; utf8, <svg width="400" height="18" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink"><path stroke="none" fill="#FFF" fill-rule="evenodd" transform="scale(0.6,0.6) translate(5,4)" d="M58.488 0.690 C 54.786 0.948,52.503 3.334,52.961 6.466 C 53.321 8.926,55.135 10.509,58.186 11.025 C 60.205 11.366,61.177 12.097,60.818 13.004 C 60.260 14.412,57.255 14.154,55.679 12.564 L 55.440 12.323 55.340 12.411 C 55.125 12.602,52.767 14.824,52.768 14.836 C 52.768 14.843,52.842 14.938,52.932 15.047 C 55.188 17.761,58.434 18.568,61.663 17.218 C 63.879 16.291,65.049 14.673,65.056 12.523 C 65.066 9.499,63.520 7.999,59.581 7.209 C 57.730 6.838,56.956 6.245,57.139 5.336 C 57.409 3.990,59.424 3.729,61.092 4.823 C 61.328 4.978,61.513 5.126,61.754 5.350 L 61.902 5.489 63.269 4.436 C 64.021 3.857,64.640 3.372,64.645 3.357 C 64.668 3.286,63.905 2.499,63.488 2.164 C 62.141 1.082,60.367 0.559,58.488 0.690 M79.453 0.691 C 76.162 0.865,73.785 2.780,73.354 5.604 C 73.306 5.919,73.281 11.980,73.325 12.570 C 73.506 14.979,75.020 16.759,77.535 17.519 C 80.709 18.479,83.881 17.374,85.557 14.725 C 85.782 14.369,85.916 14.116,85.893 14.093 C 85.872 14.073,82.327 12.430,82.254 12.406 C 82.224 12.397,82.198 12.429,82.144 12.544 C 81.882 13.103,81.353 13.555,80.730 13.752 C 79.382 14.177,77.866 13.572,77.593 12.501 C 77.539 12.288,77.540 6.228,77.595 6.015 C 78.042 4.261,81.252 4.104,82.289 5.785 C 82.338 5.865,82.385 5.930,82.393 5.930 C 82.409 5.930,85.820 4.554,85.837 4.541 C 85.856 4.526,85.497 3.838,85.340 3.588 C 84.071 1.573,82.003 0.555,79.453 0.691 M122.233 0.698 C 118.928 0.954,116.621 2.860,116.252 5.640 C 116.198 6.046,116.207 12.646,116.263 13.000 C 116.678 15.665,118.768 17.446,121.919 17.818 C 124.720 18.149,127.505 16.687,128.743 14.235 L 128.815 14.092 128.669 14.026 C 128.589 13.989,127.762 13.608,126.832 13.177 C 125.902 12.747,125.135 12.395,125.129 12.395 C 125.122 12.395,125.079 12.471,125.032 12.564 C 124.149 14.321,121.136 14.341,120.519 12.593 L 120.453 12.407 120.447 9.350 C 120.442 6.713,120.445 6.267,120.476 6.106 C 120.814 4.288,124.035 4.054,125.172 5.764 C 125.233 5.855,125.288 5.930,125.294 5.930 C 125.318 5.930,128.710 4.554,128.727 4.537 C 128.750 4.515,128.506 4.030,128.302 3.691 C 127.042 1.592,124.822 0.498,122.233 0.698 M150.163 0.690 C 146.674 0.881,144.259 2.928,144.024 5.893 C 143.992 6.292,143.992 12.111,144.024 12.535 C 144.229 15.291,146.239 17.273,149.317 17.756 C 152.815 18.304,156.021 16.678,156.902 13.907 C 157.157 13.104,157.167 12.980,157.179 10.250 L 157.190 7.907 153.816 7.907 L 150.442 7.907 150.442 9.686 L 150.442 11.465 151.770 11.465 L 153.098 11.465 153.088 11.948 C 153.069 12.840,152.771 13.335,152.028 13.707 C 150.559 14.443,148.672 13.843,148.297 12.522 L 148.244 12.337 148.244 9.221 L 148.244 6.105 148.296 5.922 C 148.641 4.708,150.215 4.096,151.595 4.640 C 152.111 4.844,152.607 5.305,152.816 5.777 C 152.852 5.859,152.875 5.885,152.903 5.877 C 152.970 5.857,156.383 4.277,156.404 4.256 C 156.456 4.205,156.028 3.438,155.709 3.012 C 154.517 1.418,152.475 0.563,150.163 0.690 M180.081 0.700 C 176.707 0.925,174.383 2.695,173.857 5.442 C 173.796 5.758,173.758 12.153,173.814 12.721 C 174.112 15.773,176.906 17.847,180.721 17.847 C 184.496 17.847,187.238 15.831,187.594 12.794 C 187.645 12.357,187.645 6.177,187.593 5.740 C 187.221 2.553,184.063 0.434,180.081 0.700 M390.026 0.701 C 386.623 0.917,384.214 2.823,383.799 5.628 C 383.750 5.958,383.722 11.716,383.765 12.444 C 383.954 15.593,386.593 17.735,390.430 17.853 C 394.202 17.969,397.090 15.976,397.551 12.938 C 397.616 12.508,397.615 6.017,397.550 5.593 C 397.065 2.452,393.986 0.450,390.026 0.701 M249.326 4.333 C 249.326 7.601,249.328 7.786,249.366 7.797 C 249.389 7.803,250.338 8.626,251.477 9.625 C 252.615 10.624,253.554 11.442,253.564 11.442 C 253.574 11.442,253.581 9.871,253.581 7.952 L 253.581 4.462 254.948 4.471 C 256.262 4.479,256.321 4.481,256.495 4.530 C 257.918 4.924,257.953 6.870,256.547 7.343 L 256.360 7.405 255.366 7.414 L 254.372 7.422 254.372 8.954 L 254.372 10.486 255.413 10.494 C 256.589 10.503,256.592 10.504,257.000 10.704 C 258.198 11.291,258.196 13.081,256.998 13.659 C 256.517 13.891,256.654 13.884,252.716 13.884 L 249.326 13.884 249.326 15.744 L 249.326 17.605 252.831 17.604 C 256.414 17.604,256.877 17.595,257.522 17.512 C 260.168 17.172,261.703 15.747,262.103 13.259 C 262.394 11.447,261.566 9.707,259.993 8.829 C 259.761 8.699,259.762 8.700,259.877 8.639 C 260.813 8.141,261.456 6.960,261.452 5.744 C 261.445 3.299,259.914 1.508,257.419 1.024 C 256.765 0.897,256.875 0.901,252.959 0.890 L 249.326 0.881 249.326 4.333 M317.842 0.913 C 317.848 0.929,319.202 4.691,320.851 9.273 L 323.849 17.604 325.791 17.604 L 327.733 17.605 330.739 9.259 C 332.392 4.669,333.744 0.907,333.744 0.899 C 333.744 0.891,332.721 0.884,331.471 0.884 L 329.198 0.884 327.877 4.983 L 326.556 9.081 326.185 11.012 C 325.982 12.073,325.815 12.955,325.814 12.971 C 325.814 12.987,325.801 13.000,325.785 13.000 C 325.765 13.000,325.639 12.389,325.380 11.025 L 325.004 9.049 323.695 4.966 L 322.385 0.884 320.109 0.884 C 318.298 0.884,317.834 0.890,317.842 0.913 M354.349 4.333 C 354.349 7.601,354.351 7.786,354.390 7.797 C 354.412 7.803,355.362 8.626,356.500 9.625 C 357.638 10.624,358.578 11.442,358.587 11.442 C 358.597 11.442,358.605 9.871,358.605 7.952 L 358.605 4.462 359.971 4.471 C 361.286 4.479,361.344 4.481,361.519 4.530 C 362.941 4.924,362.976 6.870,361.570 7.343 L 361.384 7.405 360.390 7.414 L 359.395 7.422 359.395 8.954 L 359.395 10.486 360.436 10.494 C 361.613 10.503,361.615 10.504,362.023 10.704 C 363.221 11.291,363.220 13.081,362.021 13.659 C 361.541 13.891,361.678 13.884,357.739 13.884 L 354.349 13.884 354.349 15.744 L 354.349 17.605 357.855 17.604 C 361.438 17.604,361.900 17.595,362.546 17.512 C 365.191 17.172,366.726 15.747,367.126 13.259 C 367.418 11.447,366.589 9.707,365.017 8.829 C 364.784 8.699,364.785 8.700,364.900 8.639 C 365.836 8.141,366.479 6.960,366.475 5.744 C 366.468 3.299,364.938 1.508,362.442 1.024 C 361.788 0.897,361.898 0.901,357.983 0.890 L 354.349 0.881 354.349 4.333 M24.186 4.356 C 24.186 7.624,24.188 7.809,24.227 7.820 C 24.249 7.827,25.199 8.649,26.337 9.648 C 27.476 10.647,28.415 11.465,28.424 11.465 C 28.434 11.465,28.442 9.895,28.442 7.975 L 28.442 4.485 29.808 4.494 C 31.123 4.502,31.181 4.505,31.356 4.553 C 32.778 4.947,32.813 6.893,31.407 7.366 L 31.221 7.429 30.227 7.437 L 29.233 7.445 29.233 8.977 L 29.233 10.509 30.273 10.517 C 31.450 10.527,31.452 10.527,31.860 10.727 C 33.058 11.314,33.057 13.104,31.858 13.682 C 31.378 13.914,31.515 13.907,27.576 13.907 L 24.186 13.907 24.186 15.767 L 24.186 17.628 27.692 17.627 C 31.275 17.627,31.737 17.618,32.383 17.535 C 35.028 17.195,36.564 15.770,36.964 13.282 C 37.255 11.471,36.426 9.731,34.854 8.852 C 34.621 8.722,34.622 8.724,34.738 8.662 C 35.674 8.165,36.316 6.984,36.312 5.767 C 36.305 3.322,34.775 1.531,32.279 1.047 C 31.625 0.921,31.735 0.924,27.820 0.914 L 24.186 0.904 24.186 4.356 M42.922 0.925 C 42.916 0.934,41.608 4.678,40.015 9.244 C 38.423 13.811,37.113 17.565,37.104 17.587 C 37.089 17.626,37.206 17.628,39.368 17.628 C 41.519 17.628,41.649 17.626,41.660 17.587 C 41.667 17.565,41.898 16.817,42.173 15.925 C 42.449 15.034,42.674 14.298,42.674 14.292 C 42.674 14.285,43.673 14.279,44.894 14.279 L 47.114 14.279 47.346 14.994 C 47.474 15.388,47.718 16.141,47.888 16.669 L 48.198 17.628 50.473 17.628 C 52.284 17.628,52.747 17.622,52.739 17.599 C 52.734 17.583,51.390 13.821,49.754 9.238 L 46.779 0.907 44.856 0.907 C 43.798 0.907,42.928 0.915,42.922 0.925 M66.860 9.267 L 66.860 17.628 68.977 17.628 L 71.093 17.628 71.093 9.267 L 71.093 0.907 68.977 0.907 L 66.860 0.907 66.860 9.267 M103.247 9.239 C 101.649 13.821,100.337 17.583,100.331 17.599 C 100.323 17.622,100.786 17.628,102.598 17.628 L 104.875 17.628 105.348 16.099 C 105.609 15.258,105.841 14.504,105.865 14.424 L 105.909 14.279 108.128 14.279 L 110.346 14.279 110.448 14.599 C 110.504 14.775,110.747 15.528,110.989 16.273 L 111.427 17.628 113.704 17.628 C 115.516 17.628,115.980 17.622,115.971 17.599 C 115.965 17.583,114.622 13.821,112.986 9.239 L 110.012 0.908 108.081 0.908 L 106.151 0.908 103.247 9.239 M130.326 9.267 L 130.326 17.628 132.453 17.628 L 134.581 17.628 134.581 14.740 L 134.581 11.851 134.644 11.761 C 134.696 11.686,134.711 11.676,134.731 11.705 C 134.745 11.723,135.703 13.064,136.860 14.683 L 138.965 17.627 141.648 17.627 C 144.025 17.628,144.329 17.624,144.317 17.593 C 144.308 17.568,137.994 9.268,137.789 9.011 C 137.778 8.996,139.071 7.397,141.060 4.969 C 142.869 2.759,144.349 0.941,144.349 0.929 C 144.349 0.915,143.342 0.907,141.715 0.908 L 139.081 0.909 136.837 3.975 L 134.593 7.041 134.587 3.974 L 134.581 0.907 132.453 0.907 L 130.326 0.907 130.326 9.267 M159.116 9.266 L 159.116 17.628 161.256 17.628 L 163.395 17.628 163.395 14.977 L 163.395 12.326 163.762 12.326 L 164.129 12.326 166.058 14.976 L 167.988 17.626 170.625 17.627 C 172.875 17.628,173.259 17.623,173.248 17.595 C 173.241 17.577,172.224 16.288,170.987 14.730 C 169.750 13.172,168.747 11.894,168.759 11.890 C 170.569 11.276,171.641 9.837,171.917 7.651 C 172.346 4.246,170.890 1.873,167.930 1.154 C 166.981 0.924,166.973 0.924,162.785 0.913 L 159.116 0.904 159.116 9.266 M189.767 6.704 C 189.767 12.984,189.763 12.742,189.893 13.354 C 190.564 16.526,194.059 18.450,197.907 17.766 C 200.535 17.299,202.429 15.647,202.943 13.372 C 203.088 12.729,203.079 13.167,203.087 6.750 L 203.094 0.907 200.955 0.907 L 198.815 0.907 198.808 6.599 C 198.801 11.986,198.798 12.299,198.759 12.453 C 198.236 14.492,194.735 14.570,194.112 12.558 L 194.058 12.384 194.052 6.645 L 194.046 0.907 191.907 0.907 L 189.767 0.907 189.767 6.704 M205.558 9.267 L 205.558 17.628 207.674 17.628 L 209.791 17.628 209.790 14.238 L 209.790 10.849 209.526 9.285 C 209.175 7.205,209.135 7.199,210.080 9.366 L 210.797 11.012 212.694 14.320 L 214.591 17.628 216.726 17.628 L 218.860 17.628 218.860 9.267 L 218.860 0.907 216.756 0.907 L 214.651 0.907 214.651 4.682 C 214.651 7.186,214.659 8.500,214.675 8.587 C 214.747 8.973,215.111 11.338,215.102 11.354 C 215.060 11.421,214.969 11.226,214.320 9.692 L 213.610 8.012 211.600 4.465 L 209.590 0.919 207.574 0.913 L 205.558 0.907 205.558 9.267 M221.488 4.334 C 221.488 7.579,221.491 7.763,221.529 7.774 C 221.551 7.780,222.501 8.603,223.640 9.602 C 224.778 10.601,225.717 11.418,225.727 11.418 C 225.736 11.419,225.744 9.948,225.744 8.150 L 225.744 4.881 227.087 4.889 L 228.430 4.897 228.663 4.960 C 229.357 5.146,229.767 5.539,229.922 6.163 C 229.963 6.328,229.965 6.490,229.965 9.244 L 229.965 12.151 229.913 12.349 C 229.704 13.139,229.110 13.560,228.105 13.628 C 227.923 13.641,226.390 13.651,224.634 13.651 L 221.488 13.651 221.488 15.640 L 221.488 17.628 224.738 17.628 C 228.530 17.628,228.747 17.619,229.628 17.442 C 232.189 16.927,233.789 15.382,234.170 13.058 C 234.229 12.694,234.263 6.624,234.209 5.965 C 233.966 2.989,231.727 1.114,228.198 0.930 C 227.951 0.918,226.369 0.907,224.622 0.907 L 221.488 0.907 221.488 4.334 M261.518 0.936 C 261.525 0.952,262.834 3.230,264.428 5.997 L 267.326 11.030 267.326 14.329 L 267.326 17.628 269.453 17.628 L 271.581 17.628 271.581 14.331 L 271.581 11.034 274.491 6.000 C 276.091 3.232,277.406 0.953,277.412 0.937 C 277.421 0.913,276.956 0.907,274.937 0.907 L 272.450 0.907 270.952 3.953 C 270.128 5.629,269.448 7.000,269.442 6.999 C 269.435 6.999,268.756 5.628,267.932 3.953 L 266.435 0.907 263.971 0.907 C 262.009 0.907,261.509 0.913,261.518 0.936 M290.535 4.334 C 290.535 7.579,290.537 7.763,290.576 7.774 C 290.598 7.780,291.548 8.603,292.686 9.602 C 293.824 10.601,294.764 11.418,294.773 11.418 C 294.783 11.419,294.791 9.948,294.791 8.150 L 294.791 4.881 296.134 4.889 L 297.477 4.897 297.709 4.960 C 298.403 5.146,298.814 5.539,298.968 6.163 C 299.009 6.328,299.012 6.490,299.012 9.244 L 299.012 12.151 298.959 12.349 C 298.751 13.139,298.157 13.560,297.151 13.628 C 296.970 13.641,295.436 13.651,293.680 13.651 L 290.535 13.651 290.535 15.640 L 290.535 17.628 293.785 17.628 C 297.577 17.628,297.794 17.619,298.674 17.442 C 301.235 16.927,302.836 15.382,303.216 13.058 C 303.276 12.694,303.310 6.624,303.256 5.965 C 303.013 2.989,300.774 1.114,297.244 0.930 C 296.998 0.918,295.416 0.907,293.669 0.907 L 290.535 0.907 290.535 4.334 M305.512 9.267 L 305.512 17.628 311.337 17.628 L 317.163 17.628 317.163 15.616 L 317.163 13.605 313.488 13.605 L 309.814 13.605 309.814 12.372 L 309.814 11.140 313.186 11.140 L 316.558 11.140 316.558 9.302 L 316.558 7.465 313.186 7.465 L 309.814 7.465 309.814 6.186 L 309.814 4.907 313.488 4.907 L 317.163 4.907 317.163 2.907 L 317.163 0.907 311.337 0.907 L 305.512 0.907 305.512 9.267 M334.814 9.267 L 334.814 17.628 336.942 17.628 L 339.070 17.628 339.070 9.267 L 339.070 0.907 336.942 0.907 L 334.814 0.907 334.814 9.267 M341.674 9.267 L 341.674 17.628 347.198 17.628 L 352.721 17.628 352.721 15.523 L 352.721 13.419 349.326 13.419 L 345.930 13.419 345.930 7.163 L 345.930 0.907 343.802 0.907 L 341.674 0.907 341.674 9.267 M369.070 9.267 L 369.070 17.628 371.221 17.628 L 373.372 17.628 373.372 14.977 L 373.372 12.326 373.738 12.327 L 374.105 12.328 376.034 14.978 L 377.963 17.628 380.598 17.628 C 382.047 17.628,383.232 17.620,383.232 17.610 C 383.232 17.601,382.367 16.505,381.311 15.174 C 380.254 13.844,379.235 12.561,379.047 12.324 L 378.704 11.891 378.916 11.815 C 380.927 11.094,382.015 9.124,381.947 6.327 C 381.871 3.234,380.093 1.352,376.892 0.978 C 376.397 0.920,375.607 0.908,372.424 0.907 L 369.070 0.907 369.070 9.267 M87.395 4.380 C 87.395 7.647,87.398 7.832,87.436 7.843 C 87.458 7.850,88.408 8.672,89.547 9.672 C 90.685 10.671,91.624 11.488,91.634 11.488 C 91.643 11.488,91.651 9.918,91.651 7.998 L 91.651 4.508 93.017 4.517 C 94.332 4.526,94.391 4.528,94.565 4.576 C 95.987 4.971,96.023 6.916,94.616 7.389 L 94.430 7.452 93.436 7.460 L 92.442 7.468 92.442 9.000 L 92.442 10.532 93.483 10.541 C 94.659 10.550,94.662 10.550,95.070 10.750 C 96.268 11.337,96.266 13.127,95.067 13.706 C 94.587 13.937,94.724 13.930,90.785 13.930 L 87.395 13.930 87.395 15.791 L 87.395 17.651 90.901 17.651 C 94.484 17.650,94.947 17.641,95.592 17.558 C 98.238 17.219,99.773 15.793,100.173 13.306 C 100.464 11.494,99.636 9.754,98.063 8.875 C 97.831 8.745,97.832 8.747,97.947 8.686 C 98.883 8.188,99.526 7.007,99.522 5.791 C 99.514 3.345,97.984 1.554,95.488 1.071 C 94.834 0.944,94.944 0.947,91.029 0.937 L 87.395 0.927 87.395 4.380 M181.387 4.605 C 182.483 4.791,183.204 5.337,183.359 6.098 C 183.414 6.371,183.414 12.174,183.358 12.426 C 182.924 14.391,178.570 14.432,178.069 12.475 C 178.004 12.220,177.997 6.370,178.061 6.086 C 178.311 4.984,179.776 4.331,181.387 4.605 M391.352 4.603 C 392.415 4.786,393.110 5.288,393.318 6.023 C 393.384 6.258,393.384 12.254,393.318 12.488 C 392.775 14.411,388.490 14.392,388.036 12.464 C 387.983 12.238,387.982 6.267,388.035 6.057 C 388.309 4.975,389.775 4.332,391.352 4.603 M166.461 4.949 C 168.323 5.517,168.296 8.092,166.423 8.599 L 166.198 8.660 164.797 8.669 L 163.395 8.678 163.395 6.780 L 163.395 4.881 164.843 4.889 C 166.263 4.897,166.294 4.898,166.461 4.949 M376.423 4.947 C 378.081 5.414,378.313 7.706,376.779 8.453 C 376.357 8.659,376.206 8.674,374.634 8.674 L 373.372 8.674 373.372 6.778 L 373.372 4.882 374.808 4.889 C 376.199 4.896,376.250 4.898,376.423 4.947 M44.953 5.669 C 44.953 5.679,45.210 6.770,45.523 8.093 C 45.837 9.416,46.093 10.501,46.093 10.505 C 46.093 10.509,45.538 10.512,44.859 10.512 C 43.881 10.512,43.626 10.506,43.635 10.483 C 43.641 10.467,43.916 9.373,44.247 8.052 C 44.823 5.756,44.851 5.651,44.901 5.651 C 44.930 5.651,44.953 5.659,44.953 5.669 M108.742 8.052 C 109.054 9.373,109.314 10.467,109.320 10.483 C 109.328 10.506,109.073 10.512,108.093 10.512 C 107.113 10.512,106.858 10.506,106.865 10.483 C 106.871 10.467,107.147 9.373,107.478 8.052 C 108.029 5.862,108.085 5.651,108.128 5.651 C 108.171 5.651,108.222 5.849,108.742 8.052 M5.419 9.453 L 5.419 11.465 9.105 11.465 L 12.791 11.465 12.791 9.453 L 12.791 7.442 9.105 7.442 L 5.419 7.442 5.419 9.453"></path></svg>') !important;
	display: inline !important;
	position: absolute !important;
	top: unset !important;
	left: unset !important;
	bottom: unset !important;
	right: unset !important;
	opacity: 1 !important;
	padding: 0 !important;
	margin: 0 !important;
	visibility: visible !important;
}
html > head + body > div#app-mount.appMount-3lHmkl > div.app-19_DXt > div.app-2rEoOp.vertical-V37hAW.flex-1O1GKY.directionColumn-35P_nr > div.layers-3iHuyZ.vertical-V37hAW.flex-1O1GKY.directionColumn-35P_nr.spacer-1fA9zc > div.layer-3QrUeG + div.layer-3QrUeG > div > div.standardSidebarView-3F1I7i:before {
	content: url('data:image/svg+xml; utf8, <svg width="400" height="18" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink"><path stroke="none" fill="#FFF" fill-rule="evenodd" d="M58.488 0.690 C 54.786 0.948,52.503 3.334,52.961 6.466 C 53.321 8.926,55.135 10.509,58.186 11.025 C 60.205 11.366,61.177 12.097,60.818 13.004 C 60.260 14.412,57.255 14.154,55.679 12.564 L 55.440 12.323 55.340 12.411 C 55.125 12.602,52.767 14.824,52.768 14.836 C 52.768 14.843,52.842 14.938,52.932 15.047 C 55.188 17.761,58.434 18.568,61.663 17.218 C 63.879 16.291,65.049 14.673,65.056 12.523 C 65.066 9.499,63.520 7.999,59.581 7.209 C 57.730 6.838,56.956 6.245,57.139 5.336 C 57.409 3.990,59.424 3.729,61.092 4.823 C 61.328 4.978,61.513 5.126,61.754 5.350 L 61.902 5.489 63.269 4.436 C 64.021 3.857,64.640 3.372,64.645 3.357 C 64.668 3.286,63.905 2.499,63.488 2.164 C 62.141 1.082,60.367 0.559,58.488 0.690 M79.453 0.691 C 76.162 0.865,73.785 2.780,73.354 5.604 C 73.306 5.919,73.281 11.980,73.325 12.570 C 73.506 14.979,75.020 16.759,77.535 17.519 C 80.709 18.479,83.881 17.374,85.557 14.725 C 85.782 14.369,85.916 14.116,85.893 14.093 C 85.872 14.073,82.327 12.430,82.254 12.406 C 82.224 12.397,82.198 12.429,82.144 12.544 C 81.882 13.103,81.353 13.555,80.730 13.752 C 79.382 14.177,77.866 13.572,77.593 12.501 C 77.539 12.288,77.540 6.228,77.595 6.015 C 78.042 4.261,81.252 4.104,82.289 5.785 C 82.338 5.865,82.385 5.930,82.393 5.930 C 82.409 5.930,85.820 4.554,85.837 4.541 C 85.856 4.526,85.497 3.838,85.340 3.588 C 84.071 1.573,82.003 0.555,79.453 0.691 M122.233 0.698 C 118.928 0.954,116.621 2.860,116.252 5.640 C 116.198 6.046,116.207 12.646,116.263 13.000 C 116.678 15.665,118.768 17.446,121.919 17.818 C 124.720 18.149,127.505 16.687,128.743 14.235 L 128.815 14.092 128.669 14.026 C 128.589 13.989,127.762 13.608,126.832 13.177 C 125.902 12.747,125.135 12.395,125.129 12.395 C 125.122 12.395,125.079 12.471,125.032 12.564 C 124.149 14.321,121.136 14.341,120.519 12.593 L 120.453 12.407 120.447 9.350 C 120.442 6.713,120.445 6.267,120.476 6.106 C 120.814 4.288,124.035 4.054,125.172 5.764 C 125.233 5.855,125.288 5.930,125.294 5.930 C 125.318 5.930,128.710 4.554,128.727 4.537 C 128.750 4.515,128.506 4.030,128.302 3.691 C 127.042 1.592,124.822 0.498,122.233 0.698 M150.163 0.690 C 146.674 0.881,144.259 2.928,144.024 5.893 C 143.992 6.292,143.992 12.111,144.024 12.535 C 144.229 15.291,146.239 17.273,149.317 17.756 C 152.815 18.304,156.021 16.678,156.902 13.907 C 157.157 13.104,157.167 12.980,157.179 10.250 L 157.190 7.907 153.816 7.907 L 150.442 7.907 150.442 9.686 L 150.442 11.465 151.770 11.465 L 153.098 11.465 153.088 11.948 C 153.069 12.840,152.771 13.335,152.028 13.707 C 150.559 14.443,148.672 13.843,148.297 12.522 L 148.244 12.337 148.244 9.221 L 148.244 6.105 148.296 5.922 C 148.641 4.708,150.215 4.096,151.595 4.640 C 152.111 4.844,152.607 5.305,152.816 5.777 C 152.852 5.859,152.875 5.885,152.903 5.877 C 152.970 5.857,156.383 4.277,156.404 4.256 C 156.456 4.205,156.028 3.438,155.709 3.012 C 154.517 1.418,152.475 0.563,150.163 0.690 M180.081 0.700 C 176.707 0.925,174.383 2.695,173.857 5.442 C 173.796 5.758,173.758 12.153,173.814 12.721 C 174.112 15.773,176.906 17.847,180.721 17.847 C 184.496 17.847,187.238 15.831,187.594 12.794 C 187.645 12.357,187.645 6.177,187.593 5.740 C 187.221 2.553,184.063 0.434,180.081 0.700 M390.026 0.701 C 386.623 0.917,384.214 2.823,383.799 5.628 C 383.750 5.958,383.722 11.716,383.765 12.444 C 383.954 15.593,386.593 17.735,390.430 17.853 C 394.202 17.969,397.090 15.976,397.551 12.938 C 397.616 12.508,397.615 6.017,397.550 5.593 C 397.065 2.452,393.986 0.450,390.026 0.701 M249.326 4.333 C 249.326 7.601,249.328 7.786,249.366 7.797 C 249.389 7.803,250.338 8.626,251.477 9.625 C 252.615 10.624,253.554 11.442,253.564 11.442 C 253.574 11.442,253.581 9.871,253.581 7.952 L 253.581 4.462 254.948 4.471 C 256.262 4.479,256.321 4.481,256.495 4.530 C 257.918 4.924,257.953 6.870,256.547 7.343 L 256.360 7.405 255.366 7.414 L 254.372 7.422 254.372 8.954 L 254.372 10.486 255.413 10.494 C 256.589 10.503,256.592 10.504,257.000 10.704 C 258.198 11.291,258.196 13.081,256.998 13.659 C 256.517 13.891,256.654 13.884,252.716 13.884 L 249.326 13.884 249.326 15.744 L 249.326 17.605 252.831 17.604 C 256.414 17.604,256.877 17.595,257.522 17.512 C 260.168 17.172,261.703 15.747,262.103 13.259 C 262.394 11.447,261.566 9.707,259.993 8.829 C 259.761 8.699,259.762 8.700,259.877 8.639 C 260.813 8.141,261.456 6.960,261.452 5.744 C 261.445 3.299,259.914 1.508,257.419 1.024 C 256.765 0.897,256.875 0.901,252.959 0.890 L 249.326 0.881 249.326 4.333 M317.842 0.913 C 317.848 0.929,319.202 4.691,320.851 9.273 L 323.849 17.604 325.791 17.604 L 327.733 17.605 330.739 9.259 C 332.392 4.669,333.744 0.907,333.744 0.899 C 333.744 0.891,332.721 0.884,331.471 0.884 L 329.198 0.884 327.877 4.983 L 326.556 9.081 326.185 11.012 C 325.982 12.073,325.815 12.955,325.814 12.971 C 325.814 12.987,325.801 13.000,325.785 13.000 C 325.765 13.000,325.639 12.389,325.380 11.025 L 325.004 9.049 323.695 4.966 L 322.385 0.884 320.109 0.884 C 318.298 0.884,317.834 0.890,317.842 0.913 M354.349 4.333 C 354.349 7.601,354.351 7.786,354.390 7.797 C 354.412 7.803,355.362 8.626,356.500 9.625 C 357.638 10.624,358.578 11.442,358.587 11.442 C 358.597 11.442,358.605 9.871,358.605 7.952 L 358.605 4.462 359.971 4.471 C 361.286 4.479,361.344 4.481,361.519 4.530 C 362.941 4.924,362.976 6.870,361.570 7.343 L 361.384 7.405 360.390 7.414 L 359.395 7.422 359.395 8.954 L 359.395 10.486 360.436 10.494 C 361.613 10.503,361.615 10.504,362.023 10.704 C 363.221 11.291,363.220 13.081,362.021 13.659 C 361.541 13.891,361.678 13.884,357.739 13.884 L 354.349 13.884 354.349 15.744 L 354.349 17.605 357.855 17.604 C 361.438 17.604,361.900 17.595,362.546 17.512 C 365.191 17.172,366.726 15.747,367.126 13.259 C 367.418 11.447,366.589 9.707,365.017 8.829 C 364.784 8.699,364.785 8.700,364.900 8.639 C 365.836 8.141,366.479 6.960,366.475 5.744 C 366.468 3.299,364.938 1.508,362.442 1.024 C 361.788 0.897,361.898 0.901,357.983 0.890 L 354.349 0.881 354.349 4.333 M24.186 4.356 C 24.186 7.624,24.188 7.809,24.227 7.820 C 24.249 7.827,25.199 8.649,26.337 9.648 C 27.476 10.647,28.415 11.465,28.424 11.465 C 28.434 11.465,28.442 9.895,28.442 7.975 L 28.442 4.485 29.808 4.494 C 31.123 4.502,31.181 4.505,31.356 4.553 C 32.778 4.947,32.813 6.893,31.407 7.366 L 31.221 7.429 30.227 7.437 L 29.233 7.445 29.233 8.977 L 29.233 10.509 30.273 10.517 C 31.450 10.527,31.452 10.527,31.860 10.727 C 33.058 11.314,33.057 13.104,31.858 13.682 C 31.378 13.914,31.515 13.907,27.576 13.907 L 24.186 13.907 24.186 15.767 L 24.186 17.628 27.692 17.627 C 31.275 17.627,31.737 17.618,32.383 17.535 C 35.028 17.195,36.564 15.770,36.964 13.282 C 37.255 11.471,36.426 9.731,34.854 8.852 C 34.621 8.722,34.622 8.724,34.738 8.662 C 35.674 8.165,36.316 6.984,36.312 5.767 C 36.305 3.322,34.775 1.531,32.279 1.047 C 31.625 0.921,31.735 0.924,27.820 0.914 L 24.186 0.904 24.186 4.356 M42.922 0.925 C 42.916 0.934,41.608 4.678,40.015 9.244 C 38.423 13.811,37.113 17.565,37.104 17.587 C 37.089 17.626,37.206 17.628,39.368 17.628 C 41.519 17.628,41.649 17.626,41.660 17.587 C 41.667 17.565,41.898 16.817,42.173 15.925 C 42.449 15.034,42.674 14.298,42.674 14.292 C 42.674 14.285,43.673 14.279,44.894 14.279 L 47.114 14.279 47.346 14.994 C 47.474 15.388,47.718 16.141,47.888 16.669 L 48.198 17.628 50.473 17.628 C 52.284 17.628,52.747 17.622,52.739 17.599 C 52.734 17.583,51.390 13.821,49.754 9.238 L 46.779 0.907 44.856 0.907 C 43.798 0.907,42.928 0.915,42.922 0.925 M66.860 9.267 L 66.860 17.628 68.977 17.628 L 71.093 17.628 71.093 9.267 L 71.093 0.907 68.977 0.907 L 66.860 0.907 66.860 9.267 M103.247 9.239 C 101.649 13.821,100.337 17.583,100.331 17.599 C 100.323 17.622,100.786 17.628,102.598 17.628 L 104.875 17.628 105.348 16.099 C 105.609 15.258,105.841 14.504,105.865 14.424 L 105.909 14.279 108.128 14.279 L 110.346 14.279 110.448 14.599 C 110.504 14.775,110.747 15.528,110.989 16.273 L 111.427 17.628 113.704 17.628 C 115.516 17.628,115.980 17.622,115.971 17.599 C 115.965 17.583,114.622 13.821,112.986 9.239 L 110.012 0.908 108.081 0.908 L 106.151 0.908 103.247 9.239 M130.326 9.267 L 130.326 17.628 132.453 17.628 L 134.581 17.628 134.581 14.740 L 134.581 11.851 134.644 11.761 C 134.696 11.686,134.711 11.676,134.731 11.705 C 134.745 11.723,135.703 13.064,136.860 14.683 L 138.965 17.627 141.648 17.627 C 144.025 17.628,144.329 17.624,144.317 17.593 C 144.308 17.568,137.994 9.268,137.789 9.011 C 137.778 8.996,139.071 7.397,141.060 4.969 C 142.869 2.759,144.349 0.941,144.349 0.929 C 144.349 0.915,143.342 0.907,141.715 0.908 L 139.081 0.909 136.837 3.975 L 134.593 7.041 134.587 3.974 L 134.581 0.907 132.453 0.907 L 130.326 0.907 130.326 9.267 M159.116 9.266 L 159.116 17.628 161.256 17.628 L 163.395 17.628 163.395 14.977 L 163.395 12.326 163.762 12.326 L 164.129 12.326 166.058 14.976 L 167.988 17.626 170.625 17.627 C 172.875 17.628,173.259 17.623,173.248 17.595 C 173.241 17.577,172.224 16.288,170.987 14.730 C 169.750 13.172,168.747 11.894,168.759 11.890 C 170.569 11.276,171.641 9.837,171.917 7.651 C 172.346 4.246,170.890 1.873,167.930 1.154 C 166.981 0.924,166.973 0.924,162.785 0.913 L 159.116 0.904 159.116 9.266 M189.767 6.704 C 189.767 12.984,189.763 12.742,189.893 13.354 C 190.564 16.526,194.059 18.450,197.907 17.766 C 200.535 17.299,202.429 15.647,202.943 13.372 C 203.088 12.729,203.079 13.167,203.087 6.750 L 203.094 0.907 200.955 0.907 L 198.815 0.907 198.808 6.599 C 198.801 11.986,198.798 12.299,198.759 12.453 C 198.236 14.492,194.735 14.570,194.112 12.558 L 194.058 12.384 194.052 6.645 L 194.046 0.907 191.907 0.907 L 189.767 0.907 189.767 6.704 M205.558 9.267 L 205.558 17.628 207.674 17.628 L 209.791 17.628 209.790 14.238 L 209.790 10.849 209.526 9.285 C 209.175 7.205,209.135 7.199,210.080 9.366 L 210.797 11.012 212.694 14.320 L 214.591 17.628 216.726 17.628 L 218.860 17.628 218.860 9.267 L 218.860 0.907 216.756 0.907 L 214.651 0.907 214.651 4.682 C 214.651 7.186,214.659 8.500,214.675 8.587 C 214.747 8.973,215.111 11.338,215.102 11.354 C 215.060 11.421,214.969 11.226,214.320 9.692 L 213.610 8.012 211.600 4.465 L 209.590 0.919 207.574 0.913 L 205.558 0.907 205.558 9.267 M221.488 4.334 C 221.488 7.579,221.491 7.763,221.529 7.774 C 221.551 7.780,222.501 8.603,223.640 9.602 C 224.778 10.601,225.717 11.418,225.727 11.418 C 225.736 11.419,225.744 9.948,225.744 8.150 L 225.744 4.881 227.087 4.889 L 228.430 4.897 228.663 4.960 C 229.357 5.146,229.767 5.539,229.922 6.163 C 229.963 6.328,229.965 6.490,229.965 9.244 L 229.965 12.151 229.913 12.349 C 229.704 13.139,229.110 13.560,228.105 13.628 C 227.923 13.641,226.390 13.651,224.634 13.651 L 221.488 13.651 221.488 15.640 L 221.488 17.628 224.738 17.628 C 228.530 17.628,228.747 17.619,229.628 17.442 C 232.189 16.927,233.789 15.382,234.170 13.058 C 234.229 12.694,234.263 6.624,234.209 5.965 C 233.966 2.989,231.727 1.114,228.198 0.930 C 227.951 0.918,226.369 0.907,224.622 0.907 L 221.488 0.907 221.488 4.334 M261.518 0.936 C 261.525 0.952,262.834 3.230,264.428 5.997 L 267.326 11.030 267.326 14.329 L 267.326 17.628 269.453 17.628 L 271.581 17.628 271.581 14.331 L 271.581 11.034 274.491 6.000 C 276.091 3.232,277.406 0.953,277.412 0.937 C 277.421 0.913,276.956 0.907,274.937 0.907 L 272.450 0.907 270.952 3.953 C 270.128 5.629,269.448 7.000,269.442 6.999 C 269.435 6.999,268.756 5.628,267.932 3.953 L 266.435 0.907 263.971 0.907 C 262.009 0.907,261.509 0.913,261.518 0.936 M290.535 4.334 C 290.535 7.579,290.537 7.763,290.576 7.774 C 290.598 7.780,291.548 8.603,292.686 9.602 C 293.824 10.601,294.764 11.418,294.773 11.418 C 294.783 11.419,294.791 9.948,294.791 8.150 L 294.791 4.881 296.134 4.889 L 297.477 4.897 297.709 4.960 C 298.403 5.146,298.814 5.539,298.968 6.163 C 299.009 6.328,299.012 6.490,299.012 9.244 L 299.012 12.151 298.959 12.349 C 298.751 13.139,298.157 13.560,297.151 13.628 C 296.970 13.641,295.436 13.651,293.680 13.651 L 290.535 13.651 290.535 15.640 L 290.535 17.628 293.785 17.628 C 297.577 17.628,297.794 17.619,298.674 17.442 C 301.235 16.927,302.836 15.382,303.216 13.058 C 303.276 12.694,303.310 6.624,303.256 5.965 C 303.013 2.989,300.774 1.114,297.244 0.930 C 296.998 0.918,295.416 0.907,293.669 0.907 L 290.535 0.907 290.535 4.334 M305.512 9.267 L 305.512 17.628 311.337 17.628 L 317.163 17.628 317.163 15.616 L 317.163 13.605 313.488 13.605 L 309.814 13.605 309.814 12.372 L 309.814 11.140 313.186 11.140 L 316.558 11.140 316.558 9.302 L 316.558 7.465 313.186 7.465 L 309.814 7.465 309.814 6.186 L 309.814 4.907 313.488 4.907 L 317.163 4.907 317.163 2.907 L 317.163 0.907 311.337 0.907 L 305.512 0.907 305.512 9.267 M334.814 9.267 L 334.814 17.628 336.942 17.628 L 339.070 17.628 339.070 9.267 L 339.070 0.907 336.942 0.907 L 334.814 0.907 334.814 9.267 M341.674 9.267 L 341.674 17.628 347.198 17.628 L 352.721 17.628 352.721 15.523 L 352.721 13.419 349.326 13.419 L 345.930 13.419 345.930 7.163 L 345.930 0.907 343.802 0.907 L 341.674 0.907 341.674 9.267 M369.070 9.267 L 369.070 17.628 371.221 17.628 L 373.372 17.628 373.372 14.977 L 373.372 12.326 373.738 12.327 L 374.105 12.328 376.034 14.978 L 377.963 17.628 380.598 17.628 C 382.047 17.628,383.232 17.620,383.232 17.610 C 383.232 17.601,382.367 16.505,381.311 15.174 C 380.254 13.844,379.235 12.561,379.047 12.324 L 378.704 11.891 378.916 11.815 C 380.927 11.094,382.015 9.124,381.947 6.327 C 381.871 3.234,380.093 1.352,376.892 0.978 C 376.397 0.920,375.607 0.908,372.424 0.907 L 369.070 0.907 369.070 9.267 M87.395 4.380 C 87.395 7.647,87.398 7.832,87.436 7.843 C 87.458 7.850,88.408 8.672,89.547 9.672 C 90.685 10.671,91.624 11.488,91.634 11.488 C 91.643 11.488,91.651 9.918,91.651 7.998 L 91.651 4.508 93.017 4.517 C 94.332 4.526,94.391 4.528,94.565 4.576 C 95.987 4.971,96.023 6.916,94.616 7.389 L 94.430 7.452 93.436 7.460 L 92.442 7.468 92.442 9.000 L 92.442 10.532 93.483 10.541 C 94.659 10.550,94.662 10.550,95.070 10.750 C 96.268 11.337,96.266 13.127,95.067 13.706 C 94.587 13.937,94.724 13.930,90.785 13.930 L 87.395 13.930 87.395 15.791 L 87.395 17.651 90.901 17.651 C 94.484 17.650,94.947 17.641,95.592 17.558 C 98.238 17.219,99.773 15.793,100.173 13.306 C 100.464 11.494,99.636 9.754,98.063 8.875 C 97.831 8.745,97.832 8.747,97.947 8.686 C 98.883 8.188,99.526 7.007,99.522 5.791 C 99.514 3.345,97.984 1.554,95.488 1.071 C 94.834 0.944,94.944 0.947,91.029 0.937 L 87.395 0.927 87.395 4.380 M181.387 4.605 C 182.483 4.791,183.204 5.337,183.359 6.098 C 183.414 6.371,183.414 12.174,183.358 12.426 C 182.924 14.391,178.570 14.432,178.069 12.475 C 178.004 12.220,177.997 6.370,178.061 6.086 C 178.311 4.984,179.776 4.331,181.387 4.605 M391.352 4.603 C 392.415 4.786,393.110 5.288,393.318 6.023 C 393.384 6.258,393.384 12.254,393.318 12.488 C 392.775 14.411,388.490 14.392,388.036 12.464 C 387.983 12.238,387.982 6.267,388.035 6.057 C 388.309 4.975,389.775 4.332,391.352 4.603 M166.461 4.949 C 168.323 5.517,168.296 8.092,166.423 8.599 L 166.198 8.660 164.797 8.669 L 163.395 8.678 163.395 6.780 L 163.395 4.881 164.843 4.889 C 166.263 4.897,166.294 4.898,166.461 4.949 M376.423 4.947 C 378.081 5.414,378.313 7.706,376.779 8.453 C 376.357 8.659,376.206 8.674,374.634 8.674 L 373.372 8.674 373.372 6.778 L 373.372 4.882 374.808 4.889 C 376.199 4.896,376.250 4.898,376.423 4.947 M44.953 5.669 C 44.953 5.679,45.210 6.770,45.523 8.093 C 45.837 9.416,46.093 10.501,46.093 10.505 C 46.093 10.509,45.538 10.512,44.859 10.512 C 43.881 10.512,43.626 10.506,43.635 10.483 C 43.641 10.467,43.916 9.373,44.247 8.052 C 44.823 5.756,44.851 5.651,44.901 5.651 C 44.930 5.651,44.953 5.659,44.953 5.669 M108.742 8.052 C 109.054 9.373,109.314 10.467,109.320 10.483 C 109.328 10.506,109.073 10.512,108.093 10.512 C 107.113 10.512,106.858 10.506,106.865 10.483 C 106.871 10.467,107.147 9.373,107.478 8.052 C 108.029 5.862,108.085 5.651,108.128 5.651 C 108.171 5.651,108.222 5.849,108.742 8.052"></path></svg>') !important;
	display: inline !important;
	position: absolute !important;
	left: unset !important;
	bottom: 7px !important;
	top: unset !important;
	right: 15px !important;
	opacity: 0.3 !important;
	padding: 0 !important;
	margin: 0 !important;
	visibility: visible !important;
}
html > head + body > div#app-mount.appMount-3lHmkl > div.app-19_DXt > div.app-2rEoOp.vertical-V37hAW.flex-1O1GKY.directionColumn-35P_nr > div.layers-3iHuyZ.vertical-V37hAW.flex-1O1GKY.directionColumn-35P_nr.spacer-1fA9zc > div.layer-3QrUeG + div.layer-3QrUeG > div > div.standardSidebarView-3F1I7i > div.sidebarRegion-VFTUkN > div.scrollerWrap-2lJEkd.scrollerThemed-2oenus.themeGhostHairline-DBD-2d.scrollerFade-1Ijw5y > div.scroller-2FKFPG.sidebarRegionScroller-3MXcoP > div.sidebar-CFHs9e > div.side-8zPYf6 > span#bd-settings-sidebar {
	position: relative !important;
}
html > head + body > div#app-mount.appMount-3lHmkl > div.app-19_DXt > div.app-2rEoOp.vertical-V37hAW.flex-1O1GKY.directionColumn-35P_nr > div.layers-3iHuyZ.vertical-V37hAW.flex-1O1GKY.directionColumn-35P_nr.spacer-1fA9zc > div.layer-3QrUeG + div.layer-3QrUeG > div > div.standardSidebarView-3F1I7i > div.sidebarRegion-VFTUkN > div.scrollerWrap-2lJEkd.scrollerThemed-2oenus.themeGhostHairline-DBD-2d.scrollerFade-1Ijw5y > div.scroller-2FKFPG.sidebarRegionScroller-3MXcoP > div.sidebar-CFHs9e > div.side-8zPYf6 > span#bd-settings-sidebar:after {
	content: "BasicBackground by" !important;
	font-size: 12px !important; 
	font-weight: 600 !important; 
	color: rgb(114, 118, 125) !important; 
	display: inline !important;
	opacity: 1 !important;
	padding: 2px 10px !important;
	margin: 0 !important;
	cursor: default !important;
	visibility: visible !important;
	position: relative !important;
	top: 0 !important;
	left: 0 !important;
	bottom: 0 !important;
	right: 0 !important;
}
html > head + body > div#app-mount.appMount-3lHmkl > div.app-19_DXt > div.app-2rEoOp.vertical-V37hAW.flex-1O1GKY.directionColumn-35P_nr > div.layers-3iHuyZ.vertical-V37hAW.flex-1O1GKY.directionColumn-35P_nr.spacer-1fA9zc > div.layer-3QrUeG + div.layer-3QrUeG > div > div.standardSidebarView-3F1I7i > div.sidebarRegion-VFTUkN > div.scrollerWrap-2lJEkd.scrollerThemed-2oenus.themeGhostHairline-DBD-2d.scrollerFade-1Ijw5y > div.scroller-2FKFPG.sidebarRegionScroller-3MXcoP > div.sidebar-CFHs9e > div.side-8zPYf6 > span#bd-settings-sidebar:before {
	content: "DevilBro" !important;
	font-size: 12px !important; 
	font-weight: 600 !important; 
	color: rgb(var(--vaccentcolor)) !important; 
	display: inline !important;
	opacity: 1 !important;
	padding: 0 !important;
	margin: 0 !important;
	cursor: pointer !important;
	visibility: visible !important;
	position: absolute !important;
	top: unset !important;
	left: 115px !important;
	bottom: 1px !important;
	right: 0 !important;
}
