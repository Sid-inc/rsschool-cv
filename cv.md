# Nikolay Ionov

## Contacts
* **GitHub:** [Sid-inc](https://github.com/Sid-inc)
* **Email:** [sid-sked@yandex.ru](sid-sked@yandex.ru)
* **Pone:** +7 999 000 11 22

## About myself
I want to become a frontend developer. I studied HTML, CSS and Javascript at a basic level, in RS School I want to gain practical skills in Javascript and learn the Angular framework.

## Skills
* **HTML**
  * Semantic
  * Accessibility
* **CSS**
  * SASS(SCSS)
  * BEM
* **JS basic**
* **Git**
  * Console Git
  * Github
  * Gitlab
* **Figma**

## Code example
```javascript
  window.onload = () => {
    if(todoStorage.emptyListCheck()) {
      let currentList = todoStorage.getRecord('todoItemsList');
      todoCount = currentList.length;
      let state = false;
      for (let todo in currentList) {
        (currentList[todo].state === 'finished') ? state = true : state = false;
        renderTodo(templateListItem(currentList[todo].id, currentList[todo].text, state));
      }
    }
  }
```

## Languages
* **Russian**
* **English A2**