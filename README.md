# Grayscaling-of-Video-using-OpenCV
# Methodology
![image](https://github.com/vinayparjapati5/Grayscaling-of-Video-using-OpenCV/assets/114856104/f1de1d17-8ec6-4faf-8ff7-2ea142e25f25)

# Code Explanation
This code performs the following tasks:

1. Imports the necessary libraries: `cv2` for computer vision operations and `VideoFileClip` from `moviepy.editor` for video processing.

2. Specifies the path to the input video file.

3. Creates a `VideoCapture` object using the specified video path.

4. Retrieves the video properties such as frames per second (fps), width, and height of the video.

5. Specifies the output path for the grayscale video.

6. Creates a `VideoWriter` object to write the grayscale frames to the output video file.

7. Starts a loop to process each frame of the video:

   a. Reads the next frame using the `VideoCapture` object.

   b. Checks if the frame was successfully read.

   c. Converts the frame to grayscale using the `cv2.cvtColor()` function.

   d. Writes the grayscale frame to the output video using the `write()` method of the `VideoWriter` object.

   e. Checks if the 'q' key is pressed to quit the loop.

8. Releases the video capture and writer objects.

9. Closes any OpenCV windows.

10. Adds audio to the grayscale video using `moviepy`.

11. Creates a `VideoFileClip` object for the grayscale video and another for the original video.

12. Extracts the audio from the original video clip.

13. Combines the grayscale video clip with the extracted audio using the `set_audio()` method.

14. Specifies the output path for the final video with audio.

15. Writes the final video with audio to the specified output path using the `write_videofile()` method.

16. Prints a message indicating the completion of the conversion process.

In summary, this code converts a video to grayscale using OpenCV, saves it as a new video file, and then adds the original audio back to the grayscale video using the `moviepy` library.



