# scrimba-animated-progress-bar
A <strong>pure CSS progress bar animation</strong>, designed to <strong>fill dynamically</strong> from 0% to 100% while smoothly transitioning between colors.
<h2>✨ Features</h2>
<ul>
  <li>
    <strong>CSS-only animation</strong>—no JavaScript required
  </li>
  <li>
    <strong>Color transitions</strong> from red ➡️ blue ➡️ green as progress increases
  </li>
  <li>
    <strong>Smooth filling effect</strong> using CSS <code>@keyframes</code>
  </li>
  <li>
    <strong>Looping animation</strong> with a slight pause at 100%
  </li>
</ul>
<h2>🎨 How It Works</h2>
<p>This project consists of two key elements:</p>
<ol>
  <li>
    <strong>Outer progress bar</strong> (<code>.progress-bar</code>)—acts as the container
  </li>
  <li>
    <strong>Inner progress bar</strong> (<code>.progress-status</code>)—fills dynamically
  </li>
</ol>
<h2>CSS Techniques Used</h2>
<ul>
  <li>
    <strong>Keyframe animation</strong> (<code>@keyframes filling</code>) to smoothly expand the inner bar
  </li>
  <li>
    <strong>Background color changes</strong> at key progress points
  </li>
  <li>
    <strong>CSS variables</strong> for easy color customization
  </li>
  <li>
    <strong>Overflow hidden</strong> to maintain a clean bar shape
  </li>
</ul>
