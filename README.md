# mormon-battalion

This site is all about exploring the Mormon Battalion Trail, with information, maps, blogs, podcast and more!


## Getting Started

Follow these steps to set up the project locally.

### Prerequisites

Make sure you have the following installed:

- [Git](https://git-scm.com/)
- A web browser (e.g., Chrome, Firefox)

### Installation

1. **Clone the repository**  
   Open a terminal and run:

   ```sh
   git clone https://github.com/ethyl2/mormon-battalion.git
   ```

2. **Navigate to the project folder**  

   ```sh
   cd mormon-battalion
   ```

3. **Open the project in a browser**  
   - If you are using a file-based approach, double-click `index.html` to open it.  
   - If you prefer using a local server, you can run:

     ```sh
     python -m http.server 8000  # For Python 3
     ```

     Then, open [http://localhost:8000](http://localhost:8000) in your browser.

    - Another approach is to install the VS Code extension [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer).
    Then you can right-click on the name of a HTML file in the left navigation and click on Open with Live Server.


### Adding Blog Posts

1. Create a blog post card in the Blog index page by copying and pasting an existing blog post card in blog.html, and then editing the relevant details.


```
<a href="./blog/2025-02-21-touching-the-past.html" class="group block w-full">
    <article class="border shadow rounded flex flex-col items-center justify-center space-y-2">
        <img src="./images/old-document.jpeg" alt="Mormon Battalion Trail" class="w-full h-48 object-cover rounded">
        <h3 class="text-lg font-bold text-gray-900 pt-4 px-4">Touching the Past!</h3>
        <p class="text-sm text-gray-700 px-4"><time datetime="2025-01-01">February 21, 2025</time></p>
        <p class="text-gray-800 text-sm line-clamp-2 px-4">
            We're at the National Archives this week and I got goosebumps when Laura Anderson held up this old bundle of documents and said they were records about the Detachments at Pueblo!       
        </p>
        <p class="text-blue-500 group-hover:text-blue-800 pb-4">Read More</p>
    </article>
</a>
```

2. Create a new file in the blog directory.

3. Copy an existing file from the blog directory and paste into your new file. Change whatever you'd like!

4. One tool that can be handy is chatGpt to turn normal text into HTML, with <p> tags and such, so try that out if you'd like!

## Contributing

If you'd like to contribute, please submit a pull request.

To make a new branch:

```
git checkout -b name-of-branch-goes-here

git status

git add -A

git commit -m "Your message describing the changes go here"

git push origin name-of-branch-goes-here
```

## License

This project is licensed under the [MIT License](LICENSE).

