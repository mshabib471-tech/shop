<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>HR ShopBD — Login</title>
  <meta name="description" content="Secure login and registration for HR ShopBD." />
  <script src="https://cdn.tailwindcss.com"></script>
  <script src="hr-db.js"></script>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">
  <style>
    * { box-sizing: border-box; }
    body {
      margin: 0;
      min-height: 100vh;
      font-family: Inter, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
      color: #243047;
      background:
        radial-gradient(circle at 12% 18%, rgba(177,151,255,.30), transparent 34%),
        radial-gradient(circle at 91% 56%, rgba(158,177,255,.34), transparent 37%),
        linear-gradient(135deg, #f0edff 0%, #fbf8ff 46%, #eef1ff 100%);
      overflow-x: hidden;
    }
    .orb { position: fixed; border-radius: 999px; filter: blur(70px); pointer-events:none; opacity:.45; }
    .glass {
      background: rgba(255,255,255,.63);
      border: 1px solid rgba(255,255,255,.82);
      box-shadow: 0 24px 70px rgba(76,69,113,.15), inset 0 1px 0 rgba(255,255,255,.8);
      backdrop-filter: blur(24px);
      -webkit-backdrop-filter: blur(24px);
    }
    .brand-icon {
      background: linear-gradient(135deg,#6366f1,#9a4ff3);
      box-shadow: 0 14px 30px rgba(112,78,232,.28), inset 0 1px 0 rgba(255,255,255,.35);
    }
    .gradient-text {
      background: linear-gradient(90deg,#4f46e5,#9b59f6);
      -webkit-background-clip:text; background-clip:text; color:transparent;
    }
    .tab { transition: .2s ease; color:#65738b; }
    .tab.active {
      color:#fff;
      background:linear-gradient(90deg,#5e5bed,#8b50f4);
      box-shadow:0 8px 18px rgba(108,79,235,.18);
    }
    .field {
      background: rgba(255,255,255,.72);
      border:1px solid rgba(220,224,235,.9);
      transition:.18s ease;
    }
    .field:focus-within {
      border-color:#8b6df4;
      box-shadow:0 0 0 4px rgba(112,91,235,.10);
      background:rgba(255,255,255,.9);
    }
    .field input { background:transparent; outline:none; }
    .primary-btn {
      background:linear-gradient(90deg,#6059ee,#9050f2);
      box-shadow:0 12px 25px rgba(104,79,233,.20);
      transition:.2s ease;
    }
    .primary-btn:hover { transform:translateY(-1px); filter:brightness(1.02); }
    .primary-btn:disabled { opacity:.6; cursor:not-allowed; transform:none; }
    .social-btn {
      background:rgba(255,255,255,.78);
      border:1px solid rgba(218,223,235,.95);
      transition:.18s ease;
    }
    .social-btn:hover { background:#fff; transform:translateY(-1px); }
    .divider:before,.divider:after { content:""; height:1px; flex:1; background:#dfe2eb; }
    .toast {
      position:fixed; right:20px; bottom:20px; z-index:100;
      min-width:280px; max-width:420px;
      padding:14px 16px; border-radius:16px;
      background:rgba(28,35,52,.94); color:#fff;
      box-shadow:0 18px 50px rgba(0,0,0,.18);
      opacity:0; transform:translateY(12px); pointer-events:none;
      transition:.25s ease;
    }
    .toast.show { opacity:1; transform:translateY(0); }
    .toast.error { background:rgba(185,48,80,.95); }
    .toast.success { background:rgba(22,132,91,.95); }
    .spinner { width:18px;height:18px;border:2px solid rgba(255,255,255,.45);border-top-color:#fff;border-radius:50%;animation:spin .7s linear infinite; }
    @keyframes spin { to { transform:rotate(360deg); } }
    .hidden-panel { display:none !important; }
    @media (max-width: 640px) {
      .card { width:calc(100vw - 28px); }
      .top-brand { margin-top:30px; }
      .back-btn { left:14px; top:14px; }
      .lang { right:14px; top:14px; }
      .toast { left:14px; right:14px; min-width:0; }
    }
  </style>
</head>
<body>
  <div class="orb w-72 h-72 bg-violet-300 left-[-80px] top-[80px]"></div>
  <div class="orb w-80 h-80 bg-indigo-300 right-[-100px] top-[330px]"></div>

  <a href="index.html" class="back-btn fixed left-5 top-5 z-20 inline-flex items-center gap-2 rounded-full bg-white/75 border border-white/90 px-4 py-2.5 text-sm font-semibold text-slate-600 shadow-sm backdrop-blur-xl hover:bg-white transition">
    <span>←</span><span data-i18n="back">Back to Shop</span>
  </a>

  <div class="lang fixed right-5 top-5 z-20 flex items-center gap-1 rounded-2xl bg-white/70 border border-white/90 p-1 shadow-sm backdrop-blur-xl">
    <button id="enBtn" class="rounded-xl px-3 py-2 text-xs font-bold bg-gradient-to-r from-indigo-500 to-purple-500 text-white">EN</button>
    <button id="bnBtn" class="rounded-xl px-3 py-2 text-xs font-bold text-slate-600 hover:bg-white">বাংলা</button>
  </div>

  <main class="min-h-screen flex flex-col items-center px-4 pb-6 pt-4">
    <header class="top-brand text-center mt-0 mb-7">
      <div class="brand-icon mx-auto w-16 h-16 rounded-2xl flex items-center justify-center text-white text-3xl">
        🛍️
      </div>
      <h1 class="mt-4 text-2xl font-extrabold tracking-tight text-slate-800">HR <span class="gradient-text">ShopBD</span></h1>
      <p class="mt-1 text-sm text-slate-500">Your Mobile &amp; Gadget Store ✨</p>
    </header>

    <section class="card glass w-full max-w-[450px] rounded-[26px] p-6 sm:p-7">
      <div class="grid grid-cols-2 rounded-2xl bg-white/45 p-1 mb-6">
        <button id="loginTab" class="tab active rounded-xl py-3 text-sm font-bold" type="button" data-i18n="tabLogin">Login</button>
        <button id="signupTab" class="tab rounded-xl py-3 text-sm font-bold" type="button" data-i18n="tabSignup">Sign Up</button>
      </div>

      <div id="loginPanel">
        <button id="googleLogin" type="button" class="social-btn w-full h-12 rounded-xl flex items-center justify-center gap-3 text-sm font-semibold">
          <img src="https://www.gstatic.com/firebasejs/ui/2.0.0/images/auth/google.svg" class="w-5 h-5" alt="Google">
          <span data-i18n="google">Continue with Google</span>
        </button>

        <button id="phoneLogin" type="button" class="social-btn w-full h-12 rounded-xl flex items-center justify-center gap-3 text-sm font-semibold mt-3">
          <span class="text-lg">📞</span>
          <span data-i18n="phone">Continue with Phone</span>
        </button>

        <div class="divider flex items-center gap-3 my-5 text-xs font-semibold text-slate-400">
          <span data-i18n="orEmail">or continue with email</span>
        </div>

        <form id="loginForm" class="space-y-3">
          <label class="field h-12 rounded-xl px-4 flex items-center gap-3">
            <span class="text-slate-400">✉</span>
            <input id="loginEmail" type="email" autocomplete="email" required placeholder="Email address" class="w-full text-sm text-slate-700 placeholder:text-slate-400" />
          </label>

          <label class="field h-12 rounded-xl px-4 flex items-center gap-3">
            <span class="text-slate-400">🔒</span>
            <input id="loginPassword" type="password" autocomplete="current-password" required minlength="6" placeholder="Password" class="w-full text-sm text-slate-700 placeholder:text-slate-400" />
            <button class="toggle-pass text-slate-400" type="button" data-target="loginPassword">👁</button>
          </label>

          <div class="flex items-center justify-between text-xs pt-1">
            <label class="flex items-center gap-2 text-slate-500 cursor-pointer">
              <input id="rememberMe" type="checkbox" checked class="accent-indigo-500">
              <span data-i18n="remember">Remember me</span>
            </label>
            <button id="forgotBtn" type="button" class="font-bold text-indigo-500 hover:text-indigo-700" data-i18n="forgot">Forgot Password?</button>
          </div>

          <button id="loginBtn" class="primary-btn w-full h-12 rounded-xl text-white font-bold text-sm mt-2" type="submit" data-i18n="btnLogin">Login</button>
        </form>

        <p class="text-center text-xs text-slate-400 mt-4">
          <span data-i18n="noAccount">Don't have an account?</span>
          <button id="switchSignup" class="font-bold text-indigo-500" data-i18n="tabSignup">Sign Up</button>
        </p>
      </div>

      <div id="signupPanel" class="hidden-panel">
        <button id="googleSignup" type="button" class="social-btn w-full h-12 rounded-xl flex items-center justify-center gap-3 text-sm font-semibold">
          <img src="https://www.gstatic.com/firebasejs/ui/2.0.0/images/auth/google.svg" class="w-5 h-5" alt="Google">
          <span data-i18n="google">Continue with Google</span>
        </button>

        <div class="divider flex items-center gap-3 my-5 text-xs font-semibold text-slate-400">
          <span data-i18n="orEmail">or continue with email</span>
        </div>

        <form id="signupForm" class="space-y-3">
          <label class="field h-12 rounded-xl px-4 flex items-center gap-3">
            <span class="text-slate-400">♙</span>
            <input id="signupName" type="text" autocomplete="name" required placeholder="Full name" class="w-full text-sm text-slate-700 placeholder:text-slate-400" />
          </label>
          <label class="field h-12 rounded-xl px-4 flex items-center gap-3">
            <span class="text-slate-400">✉</span>
            <input id="signupEmail" type="email" autocomplete="email" required placeholder="Email address" class="w-full text-sm text-slate-700 placeholder:text-slate-400" />
          </label>
          <label class="field h-12 rounded-xl px-4 flex items-center gap-3">
            <span class="text-slate-400">📞</span>
            <input id="signupPhone" type="tel" autocomplete="tel" placeholder="Phone number (optional)" class="w-full text-sm text-slate-700 placeholder:text-slate-400" />
          </label>
          <label class="field h-12 rounded-xl px-4 flex items-center gap-3">
            <span class="text-slate-400">🔒</span>
            <input id="signupPassword" type="password" autocomplete="new-password" required minlength="6" placeholder="Password (6+ characters)" class="w-full text-sm text-slate-700 placeholder:text-slate-400" />
            <button class="toggle-pass text-slate-400" type="button" data-target="signupPassword">👁</button>
          </label>
          <label class="field h-12 rounded-xl px-4 flex items-center gap-3">
            <span class="text-slate-400">🔒</span>
            <input id="signupConfirm" type="password" autocomplete="new-password" required minlength="6" placeholder="Confirm password" class="w-full text-sm text-slate-700 placeholder:text-slate-400" />
          </label>

          <label class="flex items-center gap-2 text-xs text-slate-500 pt-1 cursor-pointer">
            <input id="terms" type="checkbox" required class="accent-indigo-500">
            <span data-i18n="terms">I agree to the</span> <a href="#" class="font-bold text-indigo-500" data-i18n="termsLink">Terms &amp; Conditions</a>
          </label>

          <button id="signupBtn" class="primary-btn w-full h-12 rounded-xl text-white font-bold text-sm mt-2" type="submit" data-i18n="btnSignup">Create Account</button>
        </form>

        <p class="text-center text-xs text-slate-400 mt-4">
          <span data-i18n="haveAccount">Already have an account?</span>
          <button id="switchLogin" class="font-bold text-indigo-500" data-i18n="tabLogin">Login</button>
        </p>
      </div>

      <div id="phonePanel" class="hidden-panel">
        <div class="rounded-2xl bg-indigo-50/70 border border-indigo-100 p-4 text-sm text-slate-600 mb-4">
          <span data-i18n="phoneHint">Enter your phone number with country code, e.g.</span> <b>+8801XXXXXXXXX</b>.
        </div>
        <div id="recaptcha-container"></div>
        <label class="field h-12 rounded-xl px-4 flex items-center gap-3 mb-3">
          <span class="text-slate-400">📞</span>
          <input id="phoneNumber" type="tel" autocomplete="tel" placeholder="+8801XXXXXXXXX" class="w-full text-sm text-slate-700 placeholder:text-slate-400" />
        </label>
        <button id="sendCodeBtn" type="button" class="primary-btn w-full h-12 rounded-xl text-white font-bold text-sm" data-i18n="btnSendCode">Send Verification Code</button>
        <div id="codeArea" class="hidden mt-3">
          <label class="field h-12 rounded-xl px-4 flex items-center gap-3">
            <span class="text-slate-400">#</span>
            <input id="phoneCode" inputmode="numeric" autocomplete="one-time-code" maxlength="6" placeholder="6-digit verification code" class="w-full text-sm text-slate-700 placeholder:text-slate-400" />
          </label>
          <button id="verifyCodeBtn" type="button" class="primary-btn w-full h-12 rounded-xl text-white font-bold text-sm mt-3" data-i18n="btnVerify">Verify &amp; Continue</button>
          <button id="resendCodeBtn" type="button" class="w-full text-center text-[11px] font-bold text-indigo-400 hover:text-indigo-600 mt-3" data-i18n="btnResend">Resend code</button>
        </div>
        <button id="backFromPhone" type="button" class="w-full text-center text-sm font-bold text-indigo-500 mt-4" data-i18n="btnBackLogin">← Back to Login</button>
      </div>
    </section>

    <div id="envNotice" class="hidden w-full max-w-[450px] mt-3 rounded-2xl border border-amber-200 bg-amber-50/90 px-4 py-3 text-xs leading-5 text-amber-800">
      <b>Firebase:</b> Direct <code>file://</code> opening is not suitable for Firebase web authentication. Run this page on localhost or HTTPS hosting, and add the hostname to Firebase Authentication → Authorized domains.
    </div>
    <div id="setupNotice" class="hidden w-full max-w-[450px] mt-3 rounded-2xl border border-sky-200 bg-sky-50/90 px-4 py-3 text-xs leading-5 text-sky-800">
      <b>Almost ready:</b> make sure <b>Google</b> and <b>Phone</b> sign-in are enabled in Firebase Console → Authentication → Sign-in method, and that this preview domain is listed under <b>Authorized domains</b>. Then real login works.
    </div>
    <footer class="mt-6 text-[11px] text-slate-400">© <span id="yearNow"></span> HR ShopBD. All rights reserved.</footer>
  </main>

  <div id="accountBar" class="hidden fixed left-1/2 -translate-x-1/2 bottom-4 z-30 rounded-2xl bg-white/95 border border-white px-4 py-3 shadow-xl backdrop-blur-xl text-xs text-slate-600">
    <img id="barAvatar" src="" class="w-7 h-7 rounded-full object-cover inline-block align-middle mr-2 hidden">
    <span id="accountText"></span>
    <button id="continueShopBtn" class="ml-3 font-bold text-indigo-600" data-i18n="btnContinue">Go to Dashboard →</button>
    <button id="logoutBtn" class="ml-3 font-bold text-rose-500" data-i18n="btnLogoutBar">Sign out</button>
  </div>

  <div id="toast" class="toast"><div id="toastText"></div></div>

  <script type="module">
    import { initializeApp } from "https://www.gstatic.com/firebasejs/12.18.0/firebase-app.js";
    import {
      getAuth, GoogleAuthProvider, signInWithPopup, signInWithPhoneNumber,
      RecaptchaVerifier, createUserWithEmailAndPassword, signInWithEmailAndPassword,
      sendPasswordResetEmail, updateProfile, setPersistence,
      browserLocalPersistence, onAuthStateChanged, signOut
    } from "https://www.gstatic.com/firebasejs/12.18.0/firebase-auth.js";

    // ---------- tiny helpers (defined BEFORE any use) ----------
    const $ = (id) => document.getElementById(id);
    const toast = (message, type = "") => {
      $("toastText").textContent = message;
      $("toast").className = "toast show " + type;
      clearTimeout(window.__toastTimer);
      window.__toastTimer = setTimeout(() => { $("toast").className = "toast"; }, 4200);
    };

    const firebaseConfig = {
      apiKey: "AIzaSyAaLdtzOIZVYB-Bdc42CXm2T8iclWLc4o0",
      authDomain: "habib-yt.firebaseapp.com",
      projectId: "habib-yt",
      storageBucket: "habib-yt.firebasestorage.app",
      messagingSenderId: "656628491244",
      appId: "1:656628491244:web:e01ccd42bd8a2b1b4c96c9",
      measurementId: "G-GNY1T88D34"
    };

    const app = initializeApp(firebaseConfig);
    const auth = getAuth(app);

    if (location.protocol === "file:") {
      $("envNotice").classList.remove("hidden");
    }

    const googleProvider = new GoogleAuthProvider();
    googleProvider.setCustomParameters({ prompt: "select_account" });

    const friendlyError = (e) => {
      const code = e?.code || "";
      const map = {
        "auth/invalid-credential": "Email or password is incorrect.",
        "auth/invalid-login-credentials": "Email or password is incorrect.",
        "auth/user-not-found": "No account exists with this email.",
        "auth/wrong-password": "Email or password is incorrect.",
        "auth/email-already-in-use": "This email is already registered. Please login.",
        "auth/weak-password": "Password must be at least 6 characters.",
        "auth/invalid-email": "Please enter a valid email address.",
        "auth/popup-closed-by-user": "Google sign-in was cancelled.",
        "auth/popup-blocked": "Your browser blocked the Google popup. Please allow popups for this site.",
        "auth/account-exists-with-different-credential": "This email is already registered using another sign-in method.",
        "auth/too-many-requests": "Too many attempts. Please wait and try again.",
        "auth/operation-not-allowed": "This Firebase sign-in method is not enabled in Firebase Console.",
        "auth/unauthorized-domain": "This website domain is not authorized in Firebase Authentication → Authorized domains.",
        "auth/invalid-phone-number": "Enter a valid phone number with country code.",
        "auth/missing-phone-number": "Enter your phone number first.",
        "auth/quota-exceeded": "Firebase SMS quota has been exceeded. Please try again later.",
        "auth/code-expired": "The verification code has expired. Request a new code.",
        "auth/invalid-verification-code": "The verification code is incorrect.",
        "auth/captcha-check-failed": "reCAPTCHA verification failed. Please try again.",
        "auth/missing-verification-code": "Enter the 6-digit code we sent you."
      };
      return map[code] || e?.message || "Something went wrong. Please try again.";
    };

    const setBusy = (button, busy, text) => {
      if (!button) return;
      if (busy) {
        button.dataset.original = button.textContent;
        button.innerHTML = '<span class="inline-flex items-center justify-center gap-2"><span class="spinner"></span>' + text + "</span>";
        button.disabled = true;
      } else {
        button.textContent = button.dataset.original || text;
        button.disabled = false;
      }
    };

    // ---------- turn a Firebase user into the site-wide session ----------
    const providerOf = (u) => {
      try {
        const pid = (u.providerData && u.providerData[0] && u.providerData[0].providerId) || "";
        if (pid === "google.com") return "google";
        if (pid === "phone") return "phone";
        if (pid === "password") return "email";
      } catch (e) {}
      if (u.phoneNumber && !u.email) return "phone";
      return u.email ? "email" : "google";
    };
    const siteUser = (u) => ({
      uid: u.uid,
      name: u.displayName || (u.email ? u.email.split("@")[0] : "User"),
      email: u.email || "",
      phone: u.phoneNumber || "",
      photoURL: u.photoURL || "",
      provider: providerOf(u),
      joined: (u.metadata && u.metadata.creationTime) ? new Date(u.metadata.creationTime).toISOString() : new Date().toISOString()
    });
    const commitSession = (fbUser) => {
      HRDB.saveSession(siteUser(fbUser));
      localStorage.setItem("hrshop_user_email", fbUser.email || "");
    };

    // ---------- safe internal redirect ----------
    const SAFE_PAGES = ["index.html", "login.html", "dashboard.html", "checkout.html", "admin.html"];
    const safeReturnTo = () => {
      const rt = new URLSearchParams(location.search).get("returnTo") || "";
      const clean = rt.split("#")[0];
      if (clean && SAFE_PAGES.some(p => clean === p || clean.startsWith("./") === false && clean.startsWith(p + "?"))) return rt;
      return null;
    };
    const redirectAfterAuth = () => {
      const rt = safeReturnTo();
      window.location.href = rt || "dashboard.html";
    };

    // ---------- sign-in handlers ----------
    const afterSignIn = (fbUser) => {
      commitSession(fbUser);
      toast("Login successful. Welcome!", "success");
      setTimeout(redirectAfterAuth, 650);
    };

    async function loginEmail(e) {
      e.preventDefault();
      const btn = $("loginBtn");
      setBusy(btn, true, "Signing in...");
      try {
        await setPersistence(auth, browserLocalPersistence);
        const cred = await signInWithEmailAndPassword(auth, $("loginEmail").value.trim(), $("loginPassword").value);
        afterSignIn(cred.user);
      } catch (err) { toast(friendlyError(err), "error"); }
      finally { setBusy(btn, false, $("loginBtn").dataset.original || "Login"); }
    }

    async function signupEmail(e) {
      e.preventDefault();
      if (!$("terms").checked) { toast("Please accept the Terms & Conditions.", "error"); return; }
      if ($("signupPassword").value !== $("signupConfirm").value) {
        toast("Passwords do not match.", "error"); return;
      }
      const btn = $("signupBtn");
      setBusy(btn, true, "Creating account...");
      try {
        await setPersistence(auth, browserLocalPersistence);
        const cred = await createUserWithEmailAndPassword(auth, $("signupEmail").value.trim(), $("signupPassword").value);
        await updateProfile(cred.user, { displayName: $("signupName").value.trim() });
        afterSignIn(cred.user);
      } catch (err) { toast(friendlyError(err), "error"); }
      finally { setBusy(btn, false, $("signupBtn").dataset.original || "Create Account"); }
    }

    async function googleLogin() {
      try {
        await setPersistence(auth, browserLocalPersistence);
        const cred = await signInWithPopup(auth, googleProvider);
        afterSignIn(cred.user);
      } catch (err) { toast(friendlyError(err), "error"); }
    }

    async function forgotPassword() {
      const email = $("loginEmail").value.trim();
      if (!email) { toast("Enter your email address first.", "error"); $("loginEmail").focus(); return; }
      try {
        await sendPasswordResetEmail(auth, email);
        toast("Password reset email sent. Check your inbox.", "success");
      } catch (err) { toast(friendlyError(err), "error"); }
    }

    // ---------- phone (real SMS) ----------
    let recaptchaVerifier = null;
    let confirmationResult = null;

    function setupRecaptcha() {
      if (recaptchaVerifier) return recaptchaVerifier;
      recaptchaVerifier = new RecaptchaVerifier(auth, "recaptcha-container", { size: "normal" });
      return recaptchaVerifier;
    }
    function resetRecaptcha() {
      try { if (recaptchaVerifier) recaptchaVerifier.clear(); } catch (e) {}
      recaptchaVerifier = null;
      confirmationResult = null;
    }

    async function sendPhoneCode() {
      const phone = $("phoneNumber").value.trim();
      const btn = $("sendCodeBtn");
      if (!phone) { toast("Enter your phone number.", "error"); return; }
      setBusy(btn, true, "Sending...");
      try {
        await setPersistence(auth, browserLocalPersistence);
        const verifier = setupRecaptcha();
        confirmationResult = await signInWithPhoneNumber(auth, phone, verifier);
        $("codeArea").classList.remove("hidden");
        toast("Verification code sent by SMS.", "success");
      } catch (err) {
        resetRecaptcha();
        toast(friendlyError(err), "error");
      } finally { setBusy(btn, false, "Send Verification Code"); }
    }

    async function verifyPhoneCode() {
      if (!confirmationResult) { toast("Send the verification code first.", "error"); return; }
      const code = $("phoneCode").value.trim();
      if (code.length !== 6) { toast("Enter the 6-digit verification code.", "error"); return; }
      const btn = $("verifyCodeBtn");
      setBusy(btn, true, "Verifying...");
      try {
        await setPersistence(auth, browserLocalPersistence);
        const cred = await confirmationResult.confirm(code);
        resetRecaptcha();
        afterSignIn(cred.user);
      } catch (err) { toast(friendlyError(err), "error"); }
      finally { setBusy(btn, false, "Verify & Continue"); }
    }

    // ---------- panels ----------
    function showMode(mode) {
      const login = mode === "login";
      $("loginTab").classList.toggle("active", login);
      $("signupTab").classList.toggle("active", !login);
      $("loginPanel").classList.toggle("hidden-panel", !login);
      $("signupPanel").classList.toggle("hidden-panel", login);
      $("phonePanel").classList.add("hidden-panel");
    }
    function showPhone() {
      $("loginPanel").classList.add("hidden-panel");
      $("signupPanel").classList.add("hidden-panel");
      $("phonePanel").classList.remove("hidden-panel");
      setTimeout(() => { try { setupRecaptcha(); } catch (e) {} }, 150);
    }

    $("loginTab").onclick = () => showMode("login");
    $("signupTab").onclick = () => showMode("signup");
    $("switchSignup").onclick = () => showMode("signup");
    $("switchLogin").onclick = () => showMode("login");
    $("backFromPhone").onclick = () => { resetRecaptcha(); showMode("login"); };
    $("resendCodeBtn").onclick = sendPhoneCode;
    $("loginForm").addEventListener("submit", loginEmail);
    $("signupForm").addEventListener("submit", signupEmail);
    $("googleLogin").onclick = googleLogin;
    $("googleSignup").onclick = googleLogin;
    $("phoneLogin").onclick = showPhone;
    $("forgotBtn").onclick = forgotPassword;
    $("sendCodeBtn").onclick = sendPhoneCode;
    $("verifyCodeBtn").onclick = verifyPhoneCode;

    document.querySelectorAll(".toggle-pass").forEach(btn => {
      btn.onclick = () => {
        const input = $(btn.dataset.target);
        input.type = input.type === "password" ? "text" : "password";
      };
    });

    // ---------- session state ----------
    let pendingLogout = new URLSearchParams(location.search).get("action") === "logout";
    onAuthStateChanged(auth, async (user) => {
      if (pendingLogout) {
        pendingLogout = false;
        try { await signOut(auth); } catch (e) {}
        HRDB.clearSession();
        toast("Signed out successfully.", "success");
        setTimeout(() => { window.location.href = "index.html"; }, 500);
        return;
      }
      const bar = $("accountBar");
      if (user) {
        commitSession(user);
        const name = user.displayName || user.email || user.phoneNumber || "your account";
        $("accountText").textContent = "Signed in: " + name;
        if (user.photoURL) { $("barAvatar").src = user.photoURL; $("barAvatar").classList.remove("hidden"); }
        bar.classList.remove("hidden");
      } else {
        bar.classList.add("hidden");
      }
    });

    $("continueShopBtn").onclick = () => {
      const rt = safeReturnTo();
      window.location.href = rt || "dashboard.html";
    };
    $("logoutBtn").onclick = async () => {
      pendingLogout = false;
      try { await signOut(auth); } catch (e) {}
      HRDB.clearSession();
      toast("Signed out successfully.", "success");
      setTimeout(() => { window.location.href = "index.html"; }, 500);
    };

    // ---------- EN / BN ----------
    const translations = {
      en: { back:"Back to Shop", tabLogin:"Login", tabSignup:"Sign Up", btnLogin:"Login", btnSignup:"Create Account", google:"Continue with Google", phone:"Continue with Phone", orEmail:"or continue with email", remember:"Remember me", forgot:"Forgot Password?", noAccount:"Don't have an account?", haveAccount:"Already have an account?", terms:"I agree to the", termsLink:"Terms & Conditions", btnSendCode:"Send Verification Code", btnVerify:"Verify & Continue", btnResend:"Resend code", btnBackLogin:"← Back to Login", btnContinue:"Go to Dashboard →", btnLogoutBar:"Sign out", phoneHint:"Enter your phone number with country code, e.g." },
      bn: { back:"শপে ফিরে যান", tabLogin:"লগইন", tabSignup:"নিবন্ধন", btnLogin:"লগইন", btnSignup:"অ্যাকাউন্ট খুলুন", google:"Google দিয়ে চালিয়ে যান", phone:"ফোন দিয়ে চালিয়ে যান", orEmail:"অথবা ইমেইল দিয়ে চালিয়ে যান", remember:"আমাকে মনে রাখুন", forgot:"পাসওয়ার্ড ভুলে গেছেন?", noAccount:"অ্যাকাউন্ট নেই?", haveAccount:"ইতিমধ্যে অ্যাকাউন্ট আছে?", terms:"আমি সম্মত", termsLink:"শর্তাবলীতে", btnSendCode:"ভেরিফিকেশন কোড পাঠান", btnVerify:"যাচাই করুন ও চালিয়ে যান", btnResend:"কোড আবার পাঠান", btnBackLogin:"← লগইনে ফিরে যান", btnContinue:"ড্যাশবোর্ডে যান →", btnLogoutBar:"সাইন আউট", phoneHint:"কান্ট্রি কোডসহ ফোন নম্বর দিন, যেমন" }
    };
    function setLang(lang) {
      document.querySelectorAll("[data-i18n]").forEach(el => {
        const key = el.dataset.i18n;
        if (translations[lang][key]) el.textContent = translations[lang][key];
      });
      $("enBtn").className = lang === "en" ? "rounded-xl px-3 py-2 text-xs font-bold bg-gradient-to-r from-indigo-500 to-purple-500 text-white" : "rounded-xl px-3 py-2 text-xs font-bold text-slate-600 hover:bg-white";
      $("bnBtn").className = lang === "bn" ? "rounded-xl px-3 py-2 text-xs font-bold bg-gradient-to-r from-indigo-500 to-purple-500 text-white" : "rounded-xl px-3 py-2 text-xs font-bold text-slate-600 hover:bg-white";
      localStorage.setItem("hrshop_lang", lang);
    }
    $("enBtn").onclick = () => setLang("en");
    $("bnBtn").onclick = () => setLang("bn");
    setLang(localStorage.getItem("hrshop_lang") || "en");
    document.getElementById("yearNow").textContent = new Date().getFullYear();
  </script>
</body>
</html>
