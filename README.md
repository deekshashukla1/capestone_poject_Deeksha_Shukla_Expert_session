# capestone_poject_Deeksha_Shukla_Expert_session
All of the following commands should be executed in the emojibot directory
using a virtualenv with the necessary requirements listed in requirements.txt
Make sure you have the parent directory of emojibot on your PYTHONPATH

Run bot
> python bot.py /path/to/config.yaml

For help:
> python bot.py -?
(see bot.py for more info on optional command line arguments)

Linting can also be done from the emojibot directory:
pylint -j 2 emojibot

Unit tests are run from the emojibot directory:
py.test tests
