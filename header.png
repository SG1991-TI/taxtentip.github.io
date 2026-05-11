// This script controls the display of the simple disclaimer overlay.
// When the user clicks the "Agree" button, the overlay is hidden.  The
// overlay is defined in each HTML file and initially visible by default.

document.addEventListener('DOMContentLoaded', function() {
  var overlay = document.getElementById('disclaimer-overlay');
  if (!overlay) {
    return;
  }
  var acceptBtn = document.getElementById('disclaimer-accept');
  if (acceptBtn) {
    acceptBtn.addEventListener('click', function() {
      overlay.style.display = 'none';
    });
  }
});