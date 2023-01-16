# Clash Royale AI Card Tracker

Forked project from AmarSaini, updated for Jan. 2023 with all current cards/elixir values. Pixel coordinates adjusted for 1280x720 resolution (Bluestacks 11, full screen). New model generated for CNN #1, CNN #2 still works with adjusted pixel coordinates. Notably displayed elixir count is somewhat inaccurate. 

***

I wrote a report explaining how this AI Assistant was made. It's tailored towards an non-computer-science audience. Please see: [Rough Draft Report](https://github.com/AmarSaini/Clash-Royale-AI-Card-Tracker/blob/master/Clash%20Royale%20Helper/Document/Report.pdf)

Libraries Used:
- openCV (Image Preprocessing)
- Keras/TensorFlow (Convolutional Neural Networks)
- TkInter (GUI)
- PIL (Mapping images into GUI)

If you still want to see the code for the following:

1. The Convolutional Neural Network Architecture (LeNet).

2. Training the first CNN (Convolutional Nerual Network).
3. Predictions on the first CNN.
4. Live (Real-Time) predictions test on the first CNN, to learn opponent's deck.

5. Training the second CNN (Convolutional Nerual Network).
6. Predictions on the second CNN.
7. Live (Real-Time) predictions test on the second CNN, to know which card my opponent is playing.

8. Both CNN's running together during real-time to predict opponent's card cycle + elixir. (This section also has a lot of code regarding the actual AI application).

9. TkInter GUI

The code can be found here: [Clash_Royale_Helper.py](https://github.com/AmarSaini/Clash-Royale-AI-Card-Tracker/blob/master/Clash%20Royale%20Helper/Clash%20Royale%20Helper/Clash_Royale_Helper.py)

![AI Assistant](https://i.imgur.com/r4zqYmj.png)
