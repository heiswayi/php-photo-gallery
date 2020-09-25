# php-photo-gallery (WIP)

A simple photography site built with [nanogallery2](https://github.com/nanostudio-org/nanogallery2).

## Instructions

#### 1. Prepare image files

Rename your image files properly as this will be used as image title. Recommended to not more than `20` characters as by default, the title length that is more than `20` characters will be stripped from thumbnail display.

#### 2. Put image files into `photos` directory

Then, put all of your images into `photos` directory. Example of file structure:

```
./photos/
    +-- Album A
    |     +-- Picture-1.jpg
    |     +-- Picture-2.jpg
    |     +-- ...
    +-- Album B
    |     +-- Picture-3.jpg
    |     +-- Picture-4.jpg
    |     +-- ...
    +-- Picture-5.jpg
    +-- Picture-6.jpg
    +-- Picture-7.jpg
    +-- ...
```

#### 3. Make `photos` directory writable

```bash
sudo chmod -R 777 photos/
```