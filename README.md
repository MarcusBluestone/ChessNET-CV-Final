# ChessNET
A computer vision application that identifies pieces on a chess board from real-life photos.

This is a computer vision application that identifies pieces on a chess board from real-life photos and converts it to a digital format, saved in Fenn nortation. Note that the files are not fully organized into a proper package. Our paper, which describes the work in full detail, is attached as final_paper.pdf. 

## Abstract
A central problem in computer vision involves mapping real-world simulations to virtual representations. In the last decade, this has seen applications within the competitive chess community, as efficiently automating the process of converting live games into digital boards for records/analysis would save players time. Many YOLO-adapted object recognition architectures have been proposed to solve this problem using as input a single image of the game. We improve upon previous architectures by utilizing a projection function that can address a chess board oriented in any direction, and by implementing a mask so classification occurs on individual patches rather than on the entire image. This change maintains the same accuracy levels as the state-of-the-art models, while running over sixty times faster. In addition, our approach allows for extremely quick data collection and annotation. Furthermore, we propose an extension of the model to efficiently analyze video stream inputs using a binary search algorithm. This would make analysis and recording of chess games significantly simpler, as users need only to capture one video instead of a collection of photos. In total, we propose a new tool called ChessNET, which recognizes video streams of chess games and is capable of efficiently outputting the sequence of moves that were played throughout the game.


## The Process
![alt text](https://github.com/marcusbl1/ChessNET/blob/main/overview%20(1)-1.png)


