# conversationanalyser
Analyse Whatsapp conversations. An idea by [u/bartlovepuch](www.reddit.com/u/bartlovepuch) on reddit with the [post](https://www.reddit.com/r/dataisbeautiful/comments/7xicua/my_girlfriend_made_a_visualization_of_all/) in r/dataisbeautiful.

### How to use
1. On android export desired chat on whatsapp and send to computer. Select to ommit media content
2. Change filepath in import section to the chat export .txt
3. Change names in pieplot, replace `used_labels` with your ones or remove that line completely and use `labels` in the `plt.pie` instead
4. Adapt message filter to your language (also english): Change the array `filter_list` so that the first item represents the string for ommited media, the second one unanswered whatsapp calls and the third one unanswered video calls. My example is in german.

Step 2.-4. is indicated in the code as `### CHANGE: ...`
