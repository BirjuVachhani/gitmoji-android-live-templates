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

```
// TODO
```

