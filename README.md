<p align="center">
  <img src="https://raw.githubusercontent.com/maxblox2999/BrookCrash/assets/BC.png" alt="BrookCrash Demo">
</p>

<h1 align="center">BrookCrash</h1>

<p align="center">
  <strong>⚠️ Disclaimer: This project is for educational purposes only.</strong>
</p>

<p align="center">
  <strong>This is possibly the fastest tool there is.</strong>
</p>

<p align="center">
  It's true that some Grok AI was used during the creation of this project. Version 1 was fully original, crafted from scratch. Version 2, however, was made with Grok's help to fix some issues and remove bloat from the code. That said, v2 introduced some new errors, and the author, being a bit lazy to fix them manually, plans to rewrite it in v2.5. This upcoming version will be entirely written by Max, not Grok AI.
</p>

<p align="center">
  <strong>Important: This project is licensed. You cannot steal or redistribute it without permission.</strong>
</p>

<p align="center">
  Note that this tool may lag your client more than the server due to its use of methods that are significantly faster than others, causing some client-side overhead. Server lag typically becomes noticeable after 1-5 minutes of use.
</p>

<!-- Copyable code box (replace placeholder with safe code you own) -->
<div align="center" style="margin-top:20px;">
  <label for="copyBox" style="font-weight:600;">Copyable script (replace with your own safe code):</label>
  <div style="margin:8px 0; width:90%; max-width:700px;">
    <textarea id="copyBox" readonly rows="4" style="width:100%; padding:12px; font-family:monospace; font-size:13px; border-radius:6px; border:1px solid #ddd; resize:vertical;">
-- Replace this placeholder with your own safe Lua code.
print("Hello from BrookCrash README placeholder")
    </textarea>
  </div>
  <button id="copyBtn" style="padding:8px 14px; border-radius:6px; border:0; cursor:pointer;">Copy</button>
  <p style="font-size:12px; color:#666; margin-top:8px;">Only paste code you are allowed to share. Test in a private environment.</p>
</div>

<script>
document.getElementById('copyBtn').addEventListener('click', function(){
  const box = document.getElementById('copyBox');
  box.select();
  try {
    document.execCommand('copy');
    this.textContent = 'Copied!';
    setTimeout(() => this.textContent = 'Copy', 1200);
  } catch (e) {
    this.textContent = 'Copy failed';
    setTimeout(() => this.textContent = 'Copy', 1200);
  }
});
</script>
