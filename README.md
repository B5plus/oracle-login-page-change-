.custom-login-page,
body.custom-login-page {
    min-height: 100vh;
    margin: 0;
    padding: 0;
}

/* desktop background */
body.custom-login-page,
.custom-login-page .t-Body,
.custom-login-page #wwvFlowForm,
.custom-login-page .t-Body-content {
    min-height: 100vh;
    background-color: #140028 !important;
    background-image: url("#APP_IMAGES#d_login.png") !important;
    background-repeat: no-repeat !important;
    background-position: left center !important;
    background-size: cover !important;
    font-family: Arial, sans-serif;
}

/* main layout */
.custom-login-page .t-Login-container {
    min-height: 100vh !important;
    display: flex !important;
    align-items: center !important;
    justify-content: flex-end !important;
    padding: 0 90px 0 40px !important;
}

/* right panel */
.custom-login-page .t-Login-region,
.custom-login-page .t-Region,
.custom-login-page .t-Login-region .t-Region-bodyWrap,
.custom-login-page .t-Login-region .t-Region-content {
    background: rgba(24, 0, 50, 0.96) !important;
    border: none !important;
    box-shadow: none !important;
}

.custom-login-page .t-Login-region {
    width: 420px !important;
    max-width: 420px !important;
    min-height: 100vh !important;
    margin: 0 !important;
    padding: 0 42px !important;
    display: flex !important;
    flex-direction: column !important;
    justify-content: center !important;
    border-radius: 0 !important;
}

/* remove unwanted default items */
.custom-login-page .t-Login-logo,
.custom-login-page .t-Region-header,
.custom-login-page .t-Region-buttons,
.custom-login-page .a-Login-secondaryActions,
.custom-login-page .t-Form-helpButton,
.custom-login-page .js-itemHelp,
.custom-login-page .apex-item-checkbox,
.custom-login-page .checkbox_group,
.custom-login-page .t-Form-fieldContainer--checkbox {
    display: none !important;
}

/* title */
.custom-login-page .t-Login-title,
.custom-login-page .t-Region-title {
    display: block !important;
    color: #ffffff !important;
    font-size: 68px !important;
    line-height: 1 !important;
    font-weight: 800 !important;
    letter-spacing: 1px !important;
    text-transform: uppercase !important;
    margin: 0 0 28px 0 !important;
    text-align: left !important;
}

/* labels */
.custom-login-page .t-Form-label,
.custom-login-page label {
    color: #ffffff !important;
    font-size: 13px !important;
    font-weight: 600 !important;
    margin-bottom: 8px !important;
}

/* field spacing */
.custom-login-page .t-Form-fieldContainer {
    margin-bottom: 18px !important;
}

/* inputs */
.custom-login-page input[type="text"],
.custom-login-page input[type="password"] {
    width: 100% !important;
    height: 50px !important;
    border: none !important;
    border-radius: 8px !important;
    background: #2b1148 !important;
    color: #ffffff !important;
    font-size: 15px !important;
    padding: 0 16px !important;
    box-shadow: none !important;
    outline: none !important;
}

/* placeholder */
.custom-login-page input[type="text"]::placeholder,
.custom-login-page input[type="password"]::placeholder {
    color: #b8a9ce !important;
    opacity: 1 !important;
}

/* focus */
.custom-login-page input[type="text"]:focus,
.custom-login-page input[type="password"]:focus {
    background: #2b1148 !important;
    border: 1px solid #67b6ff !important;
    box-shadow: 0 0 0 2px rgba(103,182,255,0.15) !important;
}

/* button */
.custom-login-page .t-Button,
.custom-login-page button.t-Button,
.custom-login-page .ui-button {
    width: 100% !important;
    height: 52px !important;
    border: none !important;
    border-radius: 12px !important;
    background: linear-gradient(90deg, #7b2cff 0%, #63b8ff 100%) !important;
    color: #ffffff !important;
    font-size: 18px !important;
    font-weight: 700 !important;
    text-shadow: none !important;
    box-shadow: none !important;
    margin-top: 10px !important;
}

.custom-login-page .t-Button:hover,
.custom-login-page button.t-Button:hover {
    opacity: 0.96 !important;
}

/* hide any extra text under button if present */
.custom-login-page .t-Login-region p,
.custom-login-page .t-Login-region .t-Form-itemText--post,
.custom-login-page .t-Login-region .t-Form-itemText--pre {
    display: none !important;
}

/* desktop */
@media (min-width: 1024px) {
    .custom-login-page .t-Login-container {
        justify-content: flex-end !important;
        padding: 0 90px 0 40px !important;
    }

    .custom-login-page .t-Login-region {
        width: 420px !important;
        max-width: 420px !important;
        min-height: 100vh !important;
        padding: 0 42px !important;
    }
}

/* tablet */
@media (max-width: 1023px) {
    body.custom-login-page,
    .custom-login-page .t-Body,
    .custom-login-page #wwvFlowForm,
    .custom-login-page .t-Body-content {
        background-image: url("#APP_IMAGES#m_login.png") !important;
        background-repeat: no-repeat !important;
        background-position: center top !important;
        background-size: cover !important;
    }

    .custom-login-page .t-Login-container {
        justify-content: center !important;
        align-items: stretch !important;
        padding: 0 !important;
    }

    .custom-login-page .t-Login-region {
        width: 100% !important;
        max-width: 100% !important;
        min-height: 100vh !important;
        padding: 110px 24px 30px 24px !important;
        background: rgba(24, 0, 50, 0.78) !important;
    }

    .custom-login-page .t-Login-title,
    .custom-login-page .t-Region-title {
        font-size: 52px !important;
        margin-bottom: 24px !important;
    }
}

/* mobile */
@media (max-width: 640px) {
    body.custom-login-page,
    .custom-login-page .t-Body,
    .custom-login-page #wwvFlowForm,
    .custom-login-page .t-Body-content {
        background-image: url("#APP_IMAGES#m_login.png") !important;
        background-repeat: no-repeat !important;
        background-position: center top !important;
        background-size: cover !important;
    }

    .custom-login-page .t-Login-container {
        min-height: 100vh !important;
        padding: 0 !important;
        justify-content: center !important;
        align-items: stretch !important;
    }

    .custom-login-page .t-Login-region {
        width: 100% !important;
        max-width: 100% !important;
        min-height: 100vh !important;
        padding: 120px 24px 30px 24px !important;
        background: rgba(24, 0, 50, 0.74) !important;
    }

    .custom-login-page .t-Login-title,
    .custom-login-page .t-Region-title {
        font-size: 48px !important;
        margin-bottom: 22px !important;
    }

    .custom-login-page input[type="text"],
    .custom-login-page input[type="password"] {
        height: 48px !important;
        font-size: 15px !important;
    }

    .custom-login-page .t-Button,
    .custom-login-page button.t-Button {
        height: 50px !important;
        font-size: 17px !important;
    }
}





Also set these in APEX:

Page 9999 → CSS Classes
custom-login-page
Change page/login title to:
LOGIN
Change button label to:
LOGIN
Hide or remove:
Remember username
Help icon
Sign up/Register text
Social buttons

If your page still shows default APEX styling after this, send me a screenshot of Page Designer for Page 9999, and I’ll give you the exact selectors for your login page structure.
