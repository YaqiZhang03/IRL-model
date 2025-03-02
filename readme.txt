Operation Instructions: Open the "IRL model.ipynb" file and run the cells in order. (Note: The execution may take some time.)

The file "sample data.xlsx" contains example data that can be used to run the code. It includes user trajectories, where:
"user_id" represents the user identifier.
"sequence" indicates the order of user state-action pairs.
"IS", "ES", and "COM" represent the user's state in the current state-action pair, referring to Information Support received, Emotional Support received, and Companionship received.
"initiate", "self_reply", and "reply_to_others" represent the user's actions, which correspond to initiate new thread, self-reply and reply to others.

The file "reward.xlsx" is the output of running "IRL model.ipynb" on the sample data. It represents the reward values for each user, with each row corresponding to a user (including 32 reward values). The order of the users follows the input "user_id" sequence, and the order of the reward values corresponds to the sequence in the feature_matrix.