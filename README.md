# Yopu helper

<p>
    <a href="https://greasyfork.org/en/scripts/469792-yupu-helper" target="_blank">
        <img alt="GitHub Workflow Status" src="https://img.shields.io/badge/YopuHelper-Tampermonkey-orange">
    </a>
    <a href="https://github.com/Chenmo1212/Yopu-Helper" target="_blank">
        <img alt="GitHub repo size" src="https://img.shields.io/github/repo-size/Chenmo1212/Yopu-Helper">
    </a>
    <a href="https://github.com/Chenmo1212/Yopu-Helper/issues" target="_blank">
        <img alt="Issues" src="https://img.shields.io/github/issues/Chenmo1212/Yopu-Helper" />
    </a>
    <a href="https://github.com/Chenmo1212/Yopu-Helper/pulls" target="_blank">
        <img alt="GitHub pull requests" src="https://img.shields.io/github/issues-pr/Chenmo1212/Yopu-Helper" />
    </a>
    <a href="https://github.com/Chenmo1212/Yopu-Helper" target="_blank">
        <img alt="GitHub" src="https://img.shields.io/github/license/Chenmo1212/Yopu-Helper">
    </a>
<br/>
<br/>
    <a href="https://github.com/Chenmo1212/Yopu-Helper" target="_blank">
        <img alt="GitHub followers" src="https://img.shields.io/github/followers/pudongping?style=social">
    </a>
    <a href="https://github.com/Chenmo1212/Yopu-Helper" target="_blank">
        <img alt="GitHub forks" src="https://img.shields.io/github/forks/Chenmo1212/Yopu-Helper?style=social">
    </a>
    <a href="https://github.com/Chenmo1212/Yopu-Helper" target="_blank">
        <img alt="GitHub stars" src="https://img.shields.io/github/stars/Chenmo1212/Yopu-Helper?style=social">
    </a>
    <a href="https://github.com/Chenmo1212/Yopu-Helper" target="_blank">
        <img alt="GitHub watchers" src="https://img.shields.io/github/watchers/Chenmo1212/Yopu-Helper?style=social">
    </a>
</p>

![tampermonkey.png](https://cdn.chenmo1212.cn/img/tampermonkey.png)

## Description

This is a tampermonkey script written in JS. The purpose is to expand some features of the guitar score site.

You can access this website [here](https://yopu.co/?f=github).

## Features

- Print score: You can print the complete guitar score directly by clicking the `Print` button.

- Play: You can play the music of guitar without time limitations.


## Installation

- Install [Tampermonkey](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo) in your browser.

- Install this script by [Greasy Fork](https://greasyfork.org/en/scripts/469792-yupu-helper)

> If you have a problem that the content on the right cannot be completely printed when you print, please try to replace the `cdn` link of `PrintJS`. 
>
> ```js
> // @require      https://unpkg.com/print-js@1.6.0/dist/print.js
> 
> // change it to
> 
> // @require      https://printjs-4de6.kxcdn.com/print.min.js
> ```

## Contributing
Contributions are welcome! Please feel free to submit a pull request or open an issue if you find a bug or have a suggestion for a new feature.

## License
This project is licensed under the MIT License.
