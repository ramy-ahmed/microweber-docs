## thumbnail

thumbnail - Resizes an image and returns the url of the resized thumbnail

### Summary

    thumbnail($src, $width = 200, $height = 200);

### Usage

Get the picture of a post

    $content_id = 1;
    $picture_link = get_picture($content_id);

    $thumbnail = thumbnail($picture_link,150,150);

    print "<img src='".$thumbnail."' />";

 