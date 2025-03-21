# Using the [Bambot](https://github.com/timqian/bambot) Robot with LeRobot

Bambot is a two arm [lekiwi](./examples/11_use_lekiwi.md). To use Bambot with LeRobot, you can mainly follow [this doc](./examples/11_use_lekiwi.md). Expect the following difference:

1. Clone this repository instead of the official LeRobot repository. You can find the [difference here](https://github.com/huggingface/lerobot/compare/main...timqian:lerobot-bambot:main)
2. For the follower, connect 2 arms 3 wheels to the same board. The motor IDs should be set as shown below:
    <img src="./media/bambot/motor_ids.jpg" alt="Motor IDs for Bambot" title="Motor IDs for Bambot" width="60%">
3. For the leader, the motor IDs for both arms are the same, but only 12 motors are needed.
4. During calibration, ensure both arms are placed in the same position simultaneously.


