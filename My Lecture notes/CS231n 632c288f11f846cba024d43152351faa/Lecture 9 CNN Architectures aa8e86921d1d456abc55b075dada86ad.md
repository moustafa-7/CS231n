# Lecture 9 | CNN Architectures

- GoogLeNet

    ![Lecture%209%20CNN%20Architectures%20aa8e86921d1d456abc55b075dada86ad/Untitled.png](Lecture%209%20CNN%20Architectures%20aa8e86921d1d456abc55b075dada86ad/Untitled.png)

    - A problem is that the output of this is very high in volume so to fix this we add a little dimension reduction in our module.

    ![Lecture%209%20CNN%20Architectures%20aa8e86921d1d456abc55b075dada86ad/Untitled%201.png](Lecture%209%20CNN%20Architectures%20aa8e86921d1d456abc55b075dada86ad/Untitled%201.png)

    - This way makes much less operations
    - A good way to give higher importance to earlier layers is to add that auxillary classification networks and they have their own losses and stuff.
    - and not only higher importance, it is just that losses backwards can be vanished as you go deeper and deeper.

    ![Lecture%209%20CNN%20Architectures%20aa8e86921d1d456abc55b075dada86ad/Untitled%202.png](Lecture%209%20CNN%20Architectures%20aa8e86921d1d456abc55b075dada86ad/Untitled%202.png)