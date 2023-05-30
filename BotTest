# BotTest
// ==UserScript==
// @name         BingBot
// @namespace    http://tampermonkey.net/
// @version      0.1
// @description  try to take over the world!
// @author       Oksana Fedorova
// @match        https://www.bing.com/
// @icon         data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==
// @grant        none
// ==/UserScript==

//["10 самых популярных шрифтов от Google", "Отключение редакций и ревизий в WordPress", "Вывод произвольных типов записей и полей в WordPress"];09:57

let links = document.links;

let search = document.getElementsByName("search")[0];

if (search != undefined) {document.getElementsByName("q")[0].value = "купить мотоцикл";
search.click();}

for (let i = 0; i < links.length; i++)
{ if (links[i].href.indexOf("auto.ru") != -1) 
{ console.log("Я нашел строку " + links[i]);}
}
