# ICP Developer Forum
A decentralized, completely on-chain developer forum where users can post their questions attached with a bounty and others can answer them and obtain the rewards

## Features
1. Posting questions
	1. Any user can post a question with or without a bounty
	2. All post should contain the heading and the content of the question along with the relevant tags to enable users to filter questions
	3. In case of bounty questions, there are extra fields that must be filled
		1. The amount of tokens to be provided as bounty
		2. The threshold amount of upvotes that an answer must get to be rewarded
		3. The duration of the bounty period
	4. The questioner must transfer the bounty amount to the smart contract beforehand as an escrow
2. Providing answers
	1. Answers are simple and can be provided in the form of mark down or plain text
3. Upvoting questions
	1. In addition to providing answers, users can upvote a question they are interested in to increase the visibility of the question to all users
4. Upvoting answers
	1. Users can upvote any number of answers that they find useful and relevant to the respective question
5. Providing bounty
	1. Once after the bounty period is over, the reward functionality will be enabled, any user can trigger the reward function to appropriately
	2. If none of the answers are above the threshold upvotes, two functions will be enabled
		1. the questioner will be allowed to call the retract functionality to get his tokens back from the escrow
		2. The questioner will also have the choice to select answers and provide them the bounty if they feel that the answer has helped them. This is irrespective of the upvote threshold
6. Division of bounty within the answers
	1. All answers above the threshold number of upvotes are eligible for bounty
	2. The share of the bounty is determined by the number of upvotes an answer has in relation to other qualifying answers
	3. This is calculated as a percentage of the upvotes which is directly proportional to the percentage of the bounty awarded
	4. In this way, the most useful answers will obtain the highest share of the bounty

## Functions