# MS-Venkatesh--21JE0534-opencv
I have first read the given image cvtask using the cv lib. But since the image big i had to resize the image to half of its initial size
Then I converted the bgr image to grayscale for thresholding
I found out the contours present in the image and approximated the countours using the approxpolydp function.Then I wrote an if condition so that contours are drawn to the squares.
THE FOLLOWING BELOW ARE THE DIFFERENT METHODS I TRIED BUT FAILED;
(i.e. the project is incomplete)
i tried to do color detection by converting to hsv color space but certain colors were not detected due to different shades color
next i tried to compare the contours but failed to resize the markers to the markers since i coundnt get the coordinates of the corners (the image i was working on was a str)
