/* ===== PAGE 9999 LOGIN ===== */

body.t-PageBody--login,
body.t-PageBody--login .t-Body,
body.t-PageBody--login .t-Body-main,
body.t-PageBody--login .t-Body-content,
body.t-PageBody--login #wwvFlowForm {
    min-height: 100vh !important;
    margin: 0 !important;
}

body.t-PageBody--login {
    background: #120024 url("#APP_IMAGES#d_login.png") no-repeat center center / cover fixed !important;
    font-family: "Segoe UI", Arial, sans-serif !important;
    overflow-x: hidden !important;
}

/* remove page chrome */
body.t-PageBody--login .t-Header,
body.t-PageBody--login .t-Footer,
body.t-PageBody--login .t-Body-title,
body.t-PageBody--login .t-Body-nav {
    display: none !important;
}

/* desktop right dark panel */
body.t-PageBody--login .t-Login-container {
    min-height: 100vh !important;
    display: flex !important;
    justify-content: flex-end !important;
    align-items: flex-start !important;
    padding: 120px 7vw 0 0 !important;
    box-sizing: border-box !important;
    background:
        linear-gradient(
            90deg,
            rgba(13, 0, 28, 0.00) 0%,
            rgba(13, 0, 28, 0.00) 54%,
            rgba(13, 0, 28, 0.28) 54%,
            rgba(13, 0, 28, 0.74) 69%,
            rgba(13, 0, 28, 0.96) 100%
        ) !important;
}

/* login region */
#login-region,
#login-region .t-Region-bodyWrap,
#login-region .t-Region-body,
#login-region .t-Login-body,
#login-region .t-Region-content {
    background: transparent !important;
    border: none !important;
    box-shadow: none !important;
}

#login-region {
    width: 360px !important;
    max-width: 360px !important;
    min-width: 360px !important;
    margin: 0 !important;
    padding: 0 !important;
}

/* remove logo */
#login-region .t-Login-logo {
    display: none !important;
}

/* header / title */
#login-region .t-Region-header {
    background: transparent !important;
    border: 0 !important;
    box-shadow: none !important;
    padding: 0 !important;
    margin: 0 0 24px 0 !important;
}

#login-region .t-Login-title,
#login-region .t-Region-title {
    display: block !important;
    color: #ffffff !important;
    font-size: 74px !important;
    line-height: 0.95 !important;
    font-weight: 800 !important;
    letter-spacing: 1px !important;
    text-transform: uppercase !important;
    margin: 0 !important;
    text-align: left !important;
}

/* hide labels */
#P9999_USERNAME_CONTAINER .t-Form-label,
#P9999_PASSWORD_CONTAINER .t-Form-label,
#P9999_REMEMBER_CONTAINER,
#login-region .t-Form-helpButton,
#login-region .js-itemHelp,
#login-region .a-Login-secondaryActions,
#login-region p {
    display: none !important;
}

/* field spacing */
#P9999_USERNAME_CONTAINER,
#P9999_PASSWORD_CONTAINER {
    margin: 0 0 16px 0 !important;
}

#P9999_USERNAME_CONTAINER .t-Form-inputContainer,
#P9999_PASSWORD_CONTAINER .t-Form-inputContainer {
    position: relative !important;
}

/* icons */
#P9999_USERNAME_CONTAINER .t-Form-itemText--pre,
#P9999_PASSWORD_CONTAINER .t-Form-itemText--pre {
    position: absolute !important;
    left: 14px !important;
    top: 50% !important;
    transform: translateY(-50%) !important;
    margin: 0 !important;
    z-index: 2 !important;
    color: rgba(255,255,255,0.45) !important;
    font-size: 14px !important;
}

/* inputs */
#P9999_USERNAME,
#P9999_PASSWORD {
    width: 100% !important;
    height: 46px !important;
    border: none !important;
    border-radius: 8px !important;
    background: rgba(51, 20, 87, 0.96) !important;
    color: #ffffff !important;
    font-size: 15px !important;
    padding: 0 14px 0 42px !important;
    box-shadow: none !important;
    outline: none !important;
}

#P9999_USERNAME::placeholder,
#P9999_PASSWORD::placeholder {
    color: #b8acd0 !important;
    opacity: 1 !important;
}

#P9999_USERNAME:focus,
#P9999_PASSWORD:focus {
    border: 1px solid rgba(104, 184, 255, 0.95) !important;
    box-shadow: 0 0 0 2px rgba(104, 184, 255, 0.10) !important;
}

/* button area */
#login-region .t-ButtonRegion,
#login-region .t-Region-buttons {
    background: transparent !important;
    border: 0 !important;
    box-shadow: none !important;
    padding: 10px 0 0 0 !important;
    margin: 0 !important;
}

#login-region .t-Button,
#login-region button.t-Button,
#LOGIN {
    width: 100% !important;
    display: block !important;
    height: 50px !important;
    border: none !important;
    border-radius: 12px !important;
    background: linear-gradient(90deg, #7d2cff 0%, #68b8ff 100%) !important;
    color: #ffffff !important;
    font-size: 18px !important;
    font-weight: 700 !important;
    text-shadow: none !important;
    box-shadow: none !important;
    margin: 12px 0 0 0 !important;
}

#login-region .t-Button:hover,
#login-region button.t-Button:hover,
#LOGIN:hover {
    filter: brightness(1.03);
}

/* ===== MOBILE ===== */
@media (max-width: 768px) {
    body.t-PageBody--login {
        background: #120024 url("#APP_IMAGES#m_login.png") no-repeat center top / cover fixed !important;
    }

    body.t-PageBody--login .t-Login-container {
        justify-content: flex-start !important;
        align-items: stretch !important;
        padding: 0 !important;
        background:
            linear-gradient(
                180deg,
                rgba(13, 0, 28, 0.00) 0%,
                rgba(13, 0, 28, 0.10) 26%,
                rgba(13, 0, 28, 0.38) 44%,
                rgba(13, 0, 28, 0.72) 60%,
                rgba(13, 0, 28, 0.95) 100%
            ) !important;
    }

    #login-region {
        width: 100% !important;
        max-width: none !important;
        min-width: 0 !important;
        padding: 34vh 24px 30px 24px !important;
        box-sizing: border-box !important;
    }

    #login-region .t-Login-title,
    #login-region .t-Region-title {
        font-size: 56px !important;
        margin-bottom: 20px !important;
    }

    #P9999_USERNAME,
    #P9999_PASSWORD {
        height: 48px !important;
        font-size: 15px !important;
    }

    #login-region .t-Button,
    #login-region button.t-Button,
    #LOGIN {
        height: 50px !important;
        font-size: 17px !important;
    }
}

@media (max-width: 480px) {
    #login-region {
        padding: 31vh 22px 28px 22px !important;
    }

    #login-region .t-Login-title,
    #login-region .t-Region-title {
        font-size: 50px !important;
    }
}
