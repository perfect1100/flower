window.onload = () => {
  // Set a timer to delay the removal of the 'not-loaded' class
  setTimeout(() => {
    document.body.classList.remove("not-loaded");

    // Split the string into an array of characters
    const titles = 'SEMANGAT TITIIヾ(˃ᴗ˂)◞ • *✰'.split('');
    const titleElement = document.getElementById('title');
    let index = 0;

    // Set the initial font size
    titleElement.style.fontSize = '24px'; // Change this to your desired size

    // Function to append characters one by one
    function appendTitle() {
      if (index < titles.length) {
        titleElement.innerHTML += titles[index];
        index++;
        setTimeout(appendTitle, 300); // 300ms delay between characters
      }
    }

    // Start appending characters
    appendTitle();
  }, 1000); // Delay before starting the animation
};
