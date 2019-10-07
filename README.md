# GitMoji Android Live Templates

Do you know that you can use emojis in git commit messages? Many developers use emojis in the start of the commit message to make it more clear what the commit is about. It helps a lot when you're reviewing a PR or looking through commits to find something very specific. 

Here's how it looks like:

Your commit message when you write it:

```
:bug: fix some serious bug
```

Here's what it will look like on Github:

:bug: fix some serious bug

The prefix `:bug:` is converted to an emoji by Github automatically when you write it correctly. Awesome, isn't it?

Here's an awesome list of emojis and when to use them by [Carlos Cuesta](https://carloscuesta.me/): [Gitmoji](https://gitmoji.carloscuesta.me/)

## The Problem

This all looks awesome but when you will actually use it for every commit, you'll realise that it's a bit hard to remember them specially when the command is something like this: `:twisted_rightwards_arrows:`, Which eventually will be printed this: :twisted_rightwards_arrows:
It means: `Merging branches`.

Uff! so much to remember, isn't it? What if Android studio can help you remember it? what if you just write `merge` and android studio understands you what you're trying to do here and autocompletes it with `:twisted_rightwards_arrows:`? Wouldn't it be marvelous?

Well, Android Studio can do it if you can teach it how to do it!

Ah! If you're not up to teach Androd Studio how to do it(I knew that you're lazy when you skipped some reading earlier😴), keep reading further to find out how to easily do that!

## The Solution

Android Studio provides a feature called `Live Templates` which lets us do what we want(Android Studio to work for us, again!). If you haven't heard of it, [check this out](https://www.youtube.com/watch?v=4rI4tTd7-J8).

I have created live templates for these emojis. It is very easy to remember them as all you have to do it figure out what you did in that commit. e.g you did some refactorization, write refactor and press `TAB` to auto complete it into right emoji. Simple, isn't it?

Here's how you can make use of these beautifully created live templates just for you!


## How to use

1. Download **Gitmoji live templates** from [here](https://github.com/BirjuVachhani/gitmoji-android-live-templates/raw/master/settings.zip).
2. Open Android Studio and go to `File > Import Settings`.
3. Select the downloaded zip file.
4. In the `Select components to import` dialog, hit `ok`.
5. Congrats! You've done it in first try!

To confirm that the live templates are imported successfully, go to 


## Available Gitmojis

| **No** | **Abbreviation** | **Actual Template Text**      | **Description**                             | **Gitmoji**                 |
|--------|------------------|-------------------------------|---------------------------------------------|-----------------------------|
| 1      | access           | `:wheelchair:`                | Improving accessibility.                    | :wheelchair:                |
| 2      | addci            | `:construction_worker:`       | Adding CI build system.                     | :construction_worker:       |
| 3      | adddep           | `:heavy_plus_sign:`           | Adding a dependency.                        | :heavy_plus_sign:           |
| 4      | analytics        | `:chart_with_upwards_trend:`  | Adding analytics or tracking code.          | :chart_with_upwards_trend:  |
| 5      | arch             | `:building_construction:`     | Making architectural changes.               | :building_construction:     |
| 6      | assets           | `:bento:`                     | Adding or updating assets.                  | :bento:                     |
| 7      | bad              | `:poop:`                      | Writing bad code that needs to be improved. | :poop:                      |
| 8      | breaking         | `:boom:`                      | Introducing breaking changes.               | :boom:                      |
| 9      | bug              | `:bug:`                       | Fixing a bug.                               | :bug:                       |
| 10     | ci               | `:green_heart:`               | Fixing CI Build.                            | :green_heart:               |
| 11     | comment          | `:bulb:`                      | Documenting source code.                    | :bulb:                      |
| 12     | config           | `:wrench:`                    | Changing configuration files.               | :wrench:                    |
| 13     | db               | `:card_file_box:`             | Performing database related changes.        | :card_file_box:             |
| 14     | degrade          | `:arrow_down:`                | Downgrading dependencies.                   | :arrow_down:                |
| 15     | deploy           | `:rocket:`                    | Deploying stuff.                            | :rocket:                    |
| 16     | docs             | `:pencil:`                    | Writing docs.                               | :pencil:                    |
| 17     | exp              | `:alembic:`                   | Experimenting new things                    | :alembic:                   |
| 18     | feat             | `:sparkles:`                  | Introducing new features.                   | :sparkles:                  |
| 19     | gitignore        | `:see_no_evil:`               | Adding or updating a `.gitignore` file      | :see_no_evil:               |
| 20     | hotfix           | `:ambulance:`                 | Critical hotfix.                            | :ambulance:                 |
| 21     | init             | `:tada:`                      | Initial commit.                             | :tada:                      |
| 22     | merge            | `:twisted_rightwards_arrows:` | Merging branches.                           | :twisted_rightwards_arrows: |
| 23     | move             | `:truck:`                     | Moving or renaming files.                   | :truck:                     |
| 24     | perf             | `:zap:`                       | Improving performance.                      | :zap:                       |
| 25     | refactor         | `:recycle:`                   | Refactoring code.                           | :recycle:                   |
| 26     | release          | `:bookmark:`                  | Releasing / Version tags.                   | :bookmark:                  |
| 27     | remove           | `:fire:`                      | Removing code or files.                     | :fire:                      |
| 28     | rename           | `:truck:`                     | Moving or renaming files.                   | :truck:                     |
| 29     | responsive       | `:iphone:`                    | Working on responsive design.               | :iphone:                    |
| 30     | revert           | `:rewind:`                    | Reverting changes.                          | :rewind:                    |
| 31     | review           | `:ok_hand:`                   | Updating code due to code review changes.   | :ok_hand:                   |
| 32     | rmdep            | `:heavy_minus_sign:`          | Removing a dependency.                      | :heavy_minus_sign:          |
| 33     | rmlog            | `:mute:`                      | Removing logs.                              | :mute:                      |
| 34     | security         | `:lock:`                      | Fixing security issues.                     | :lock:                      |
| 35     | struct           | `:art:`                       | Improving structure / format of the code.   | :art:                       |
| 36     | test             | `:white_check_mark:`          | Updating tests.                             | :white_check_mark:          |
| 37     | text             | `:speech_balloon:`            | Updating text and literals.                 | :speech_balloon:            |
| 38     | typo             | `:pencil2:`                   | Fixing typos.                               | :pencil2:                   |
| 39     | ui               | `:lipstick:`                  | Updating the UI and style files.            | :lipstick:                  |
| 40     | upgrade          | `:arrow_up:`                  | Upgrading dependencies.                     | :arrow_up:                  |
| 41     | ux               | `:children_crossing:`         | Improving user experience / usability.      | :children_crossing:         |

### Pull Request
To generate a pull request, please consider following [Pull Request Template](https://github.com/BirjuVachhani/gitmoji-android-live-templates/blob/master/PULL_REQUEST_TEMPLATE.md).

### Issues
To submit an issue, please check the [Issue Template](https://github.com/BirjuVachhani/lgitmoji-android-live-templates/blob/master/ISSUE_TEMPLATE.md).

Code of Conduct
---
[Code of Conduct](https://github.com/BirjuVachhani/gitmoji-android-live-templates/blob/master/CODE_OF_CONDUCT.md)

## Contribution

You are most welcome to contribute to this project!

Please have a look at [Contributing Guidelines](https://github.com/BirjuVachhani/gitmoji-android-live-templates/blob/master/CONTRIBUTING.md), before contributing and proposing a change.

## License

```
Copyright © 2019 Birju Vachhani

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
