# Maksim Malashkov
### __Personal information:__
>Education:

Systems Engineer,
Belarusian-Russian University (2022)

>Location:

Mogilev, Belarus

>Spoken languages:

- Russian
- Belarusian
- English (A2)

>Contacts:

- Phone: +375295450399 (MTC)
- Email: max.malaschkov@mail.ru
- Telegram: @KalashnikovTV

>About myself:

I am a very responsible and purposeful person, full of energy and determination to achieve my goals and desired results.

I am looking for a job where I can develop and improve my skills.

### __Skills:__

- HTML/CSS
- SASS/SCSS
- JavaScript
- Bootstrap
- Webpack/Gulp
- Git
- BEM

>Code examples:
```
function tabs(tabsSelector, tabsContentSelector, tabsParentSelector, activeClass) {
    const tabs = document.querySelectorAll(tabsSelector),
        tabsContent = document.querySelectorAll(tabsContentSelector),
        tabsParent = document.querySelector(tabsParentSelector);

    function hideTabContent() {
        tabsContent.forEach(item => {
            item.classList.add('hide');
            item.classList.remove('show', 'fade');
        });

        tabs.forEach(item => {
            item.classList.remove(activeClass);
        });
    }

    function showTabContent(i = 0) {
        tabsContent[i].classList.add('show', 'fade');
        tabsContent[i].classList.remove('hide');
        tabs[i].classList.add(activeClass);
    }

    hideTabContent();
    showTabContent();

    tabsParent.addEventListener('click', (event) => {
        const target = event.target;

        if (target && target.classList.contains(tabsSelector.slice(1))) {
            tabs.forEach((item, i) => {
                if (target == item) {
                    hideTabContent();
                    showTabContent(i);
                }
            });
        }
    });
}

export default tabs;
```

### __Work experience:__
- Responsive HTML template
- Course "From 0 to 1" (Markup Developer) by Vadim Prokopchuk [click](http://prntscr.com/xm4sn5)
- Course on Coursera  "The basics of programming in Python" [click](http://prntscr.com/xm4znz)
- Completed JavaScript courses by Ivan Petrichenko
- Coding in the University
