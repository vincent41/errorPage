# HTML Simple Maintenance Page

"HTML Simple Maintenance Page" is a maintenance page in a very light HTML format requiring only one file.

## Preview

![enter image description here](https://raw.githubusercontent.com/theoricher/Simple-Maintenance-Page/master/preview.jpg)

# License

- Icons: [Icons8.com](https://icons8.com/)

# Install

1.  git clone https://github.com/theoricher/Simple-Maintenance-Page.git
2.  nano Dockerfile
    FROM nginx
    COPY . /usr/share/nginx/html
3.  docker build -t error-page .
4.  docker run -d -p 5500:80 error-page
