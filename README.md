/* =========================================================
   DELETE OLD CSS FIRST
   Images used:
   #APP_IMAGES#d_login.png
   #APP_IMAGES#m_login.png
   ========================================================= */

/* full page */
body.custom-login-page.t-PageBody--login,
body.custom-login-page.t-PageBody--login .t-Body,
body.custom-login-page.t-PageBody--login #wwvFlowForm,
body.custom-login-page.t-PageBody--login .t-Body-content {
    min-height: 100vh !important;
    margin: 0 !important;
    background: #120021 url("#APP_IMAGES#d_login.png") no-repeat center center / cover !important;
    font-family: "Segoe UI", Arial, sans-serif !important;
    overflow-x: hidden !important;
}

/* hide header/footer */
body.custom-login-page .t-Header,
body.custom-login-page .t-Footer,
body.custom-login-page .t-Body-nav,
body.custom-login-page .t-Body-title {
    display: none !important;
}

/* desktop split overlay */
body.custom-login-page .t-Login-container {
    min-height: 100vh !important;
    display: flex !important;
    justify-content: flex-end !important;
    align-items: flex-start !important;
    padding: 14vh 7vw 0 0 !important;
    box-sizing: border-box !important;
    background:
        linear-gradient(
            90deg,
            rgba(12, 0, 28, 0.00) 0%,
            rgba(12, 0, 28, 0.00) 55%,
            rgba(18, 0, 40, 0.55) 55%,
            rgba(18, 0, 40, 0.82) 72%,
            rgba(18, 0, 40, 0.96) 100%
        ) !important;
}

/* main form area */
body.custom-login-page #login-panel,
body.custom-login-page #login-panel .t-Region-bodyWrap,
body.custom-login-page #login-panel .t-Region-body,
body.custom-login-page #login-panel .t-Region-content {
    background: transparent !important;
    border: none !important;
    box-shadow: none !important;
}

body.custom-login-page #login-panel {
    position: relative !important;
    width: min(31vw, 420px) !important;
    min-width: 340px !important;
    margin: 0 !important;
    padding: 0 !important;
}

/* remove default APEX header/logo */
body.custom-login-page #login-panel .t-Region-header,
body.custom-login-page #login-panel .t-Login-logo,
body.custom-login-page #login-panel .t-Region-buttons {
    display: none !important;
}

/* add title exactly by CSS */
body.custom-login-page #login-panel::before {
    content: "LOGIN";
    display: block;
    color: #ffffff;
    font-size: clamp(54px, 5vw, 78px);
    font-weight: 800;
    line-height: 0.95;
    letter-spacing: 1px;
    margin: 0 0 28px 0;
    text-transform: uppercase;
}

/* hide default labels/text if they show */
body.custom-login-page #login-panel .t-Form-label,
body.custom-login-page #login-panel .t-Form-itemText--pre,
body.custom-login-page #login-panel .t-Form-itemText--post,
body.custom-login-page #login-panel .t-Form-helpButton,
body.custom-login-page #login-panel .js-itemHelp,
body.custom-login-page #login-panel .apex-item-checkbox,
body.custom-login-page #login-panel .checkbox_group,
body.custom-login-page #login-panel .t-Form-fieldContainer--checkbox,
body.custom-login-page #login-panel .a-Login-secondaryActions {
    display: none !important;
}

/* spacing */
body.custom-login-page #login-panel .t-Form-fieldContainer {
    margin: 0 0 18px 0 !important;
}

body.custom-login-page #login-panel .t-Form-itemWrapper,
body.custom-login-page #login-panel .t-Form-inputContainer,
body.custom-login-page #login-panel .apex-item-wrapper {
    width: 100% !important;
    max-width: 100% !important;
}

/* inputs */
body.custom-login-page #login-panel input[type="text"],
body.custom-login-page #login-panel input[type="password"] {
    width: 100% !important;
    height: 46px !important;
    background: rgba(48, 19, 84, 0.96) !important;
    border: none !important;
    border-radius: 8px !important;
    color: #ffffff !important;
    font-size: 15px !important;
    padding: 0 14px !important;
    box-shadow: none !important;
    outline: none !important;
}

/* placeholder */
body.custom-login-page #login-panel input[type="text"]::placeholder,
body.custom-login-page #login-panel input[type="password"]::placeholder {
    color: #b8acd1 !important;
    opacity: 1 !important;
}

/* focus */
body.custom-login-page #login-panel input[type="text"]:focus,
body.custom-login-page #login-panel input[type="password"]:focus {
    border: 1px solid rgba(105, 185, 255, 0.9) !important;
    box-shadow: 0 0 0 2px rgba(105, 185, 255, 0.12) !important;
}

/* button */
body.custom-login-page #login-panel .t-Button,
body.custom-login-page #login-panel button.t-Button,
body.custom-login-page #login-panel .ui-button {
    width: 100% !important;
    height: 50px !important;
    margin-top: 14px !important;
    border: none !important;
    border-radius: 12px !important;
    background: linear-gradient(90deg, #7d2cff 0%, #68b8ff 100%) !important;
    color: #ffffff !important;
    font-size: 18px !important;
    font-weight: 700 !important;
    text-shadow: none !important;
    box-shadow: none !important;
}

body.custom-login-page #login-panel .t-Button:hover,
body.custom-login-page #login-panel button.t-Button:hover {
    filter: brightness(1.03);
}

/* remove strange extra paragraph text if any */
body.custom-login-page #login-panel p {
    display: none !important;
}

/* =========================
   TABLET + MOBILE
   ========================= */
@media (max-width: 900px) {
    body.custom-login-page.t-PageBody--login,
    body.custom-login-page.t-PageBody--login .t-Body,
    body.custom-login-page.t-PageBody--login #wwvFlowForm,
    body.custom-login-page.t-PageBody--login .t-Body-content {
        background: #120021 url("#APP_IMAGES#m_login.png") no-repeat center top / cover !important;
    }

    body.custom-login-page .t-Login-container {
        min-height: 100vh !important;
        justify-content: flex-start !important;
        align-items: stretch !important;
        padding: 0 !important;
        background:
            linear-gradient(
                180deg,
                rgba(12, 0, 28, 0.06) 0%,
                rgba(12, 0, 28, 0.16) 28%,
                rgba(12, 0, 28, 0.40) 45%,
                rgba(12, 0, 28, 0.72) 62%,
                rgba(12, 0, 28, 0.92) 100%
            ) !important;
    }

    body.custom-login-page #login-panel {
        width: 100% !important;
        min-width: 0 !important;
        max-width: none !important;
        padding: 34vh 24px 32px 24px !important;
        box-sizing: border-box !important;
    }

    body.custom-login-page #login-panel::before {
        font-size: 56px !important;
        margin-bottom: 20px !important;
    }

    body.custom-login-page #login-panel input[type="text"],
    body.custom-login-page #login-panel input[type="password"] {
        height: 48px !important;
        font-size: 15px !important;
    }

    body.custom-login-page #login-panel .t-Button,
    body.custom-login-page #login-panel button.t-Button {
        height: 50px !important;
        font-size: 17px !important;
    }
}

/* smaller phones */
@media (max-width: 480px) {
    body.custom-login-page #login-panel {
        padding: 31vh 22px 28px 22px !important;
    }

    body.custom-login-page #login-panel::before {
        font-size: 52px !important;
    }
}
