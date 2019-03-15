---
lang: ru
title: Лучшие практики для сторонников
description: Облегчение вашей жизни в качестве сторонника открытого исходнго кода, от документирования процессов до использования вашего сообщества.
class: best-practices
toc:
  what-does-it-mean-to-be-a-maintainer: "Что значит быть сторонником?"
  documenting-your-processes: "Документирование ваших процессов"
  learning-to-say-no: "Учимся говорить нет"
  leverage-your-community: "Используйте ваше сообщество"
  bring-in-the-robots: "Задействуйте роботов"
  its-okay-to-hit-pause: "Это нормально - брать паузу"
order: 5
image: /assets/images/cards/best-practices.png
related:
  - метрики
  - лидерство
---

## Что значит быть сторонником?

Если вы являетесь участником проекта с открытым исходным кодом которым пользуется много людей, вы могли заметить, что вы меньше пишете и больше отвечаете на вопросы.

На ранних стадиях проекта, вы экспериментируете с новыми идеями и принимаете решения на основе того, что вы хотите. По мере того, как ваш проект становится все популярнее, вы обнаружите, что работаете со своими пользователями и участниками..

Поддержание проекта требует не только кода. Эти задачи часто бывают неожиданными, но они так же важны для растущего проекта. Мы собрали несколько способов сделать вашу жизнь проще, от документирования процессов до использования вашего сообщества.

## Документирование ваших процессов

Записывать вещи - одна из самых важных вещей, которую вы можете сделать как сопровождающий.

Документация не только проясняет ваше собственное мышление, но это помогает другим людям понять, что вам нужно или ожидать, прежде чем они даже спросят.

Записывая вещи, легче сказать «нет», когда что-то не вписывается в твою сферу. Это также облегчает людям возможность участвовать и помогать. Вы никогда не знаете, кто может читать или использовать ваш проект.

ДАже если вы не записываете целые параграфы, отметить ключевые моменты все же лучше чем не писать вообще.

Не забывайте регулярно обновлять документацию. Если вы не всегда можете это сделать, удалите устаревшую документацию или укажите, что она устарела, чтобы участники знали, что обновления приветствуются.

### Запишите видение вашего проекта

Начните с записи целей вашего проекта. Добавьте их в свой README, или создайте отдельный файл с именем VISION. Если есть другие артефакты, которые могут помочь, например дорожная карта проекта, сделайте их публичными..

Наличие четкого, документированного видения держит вас в фокусе и помогает избежать "scope creep" от других участников.

Например, @lord обнаружил, что наличие видения проекта помогло ему выяснить, на какие запросы тратить время. Как новый сопровождающий, он сожалел, что не придерживался масштабов своего проекта, когда получил свой первый запрос на добавление [Slate](https://github.com/lord/slate).

<aside markdown="1" class="pquote">
  <img src="https://avatars.githubusercontent.com/lord?s=180" class="pquote-avatar" alt="avatar">
  Я завозился. Я не приложил усилий, чтобы найти полное решение. Вместо недоделанного решения, Хотелось бы, чтобы я сказал: «У меня сейчас нет времени на это, но я добавлю его в долгосрочный список желаний»."
  <p markdown="1" class="pquote-credit">
— @lord, ["Советы для новых разработчиков с открытым исходным кодом"](https://lord.io/blog/2014/oss-tips/)
  </p>
</aside>

### Сообщите свои ожидания

Написание правил может нервировать. Иногда вы можете чувствовать, что контролируете поведение других людей или убиваете все веселье.

Но написанные и соблюдаемые честно, хорошие правила помогают сопровождающим. Они мешают вам увлекаться тем, что вы не хотите делать.

Большинство людей, которые сталкиваются с вашим проектом, ничего не знают о вас или ваших обстоятельствах. Они могут предположить, что вам платят за работу, особенно если это то, что они регулярно используют и от чего зависят. Возможно, в какой-то момент вы потратили много времени на свой проект, но теперь вы заняты новой работой или членом семьи.

Все это совершенно нормально! Просто убедитесь, что другие люди знают об этом.

Если ведение вашего проекта занято неполный рабочий день или является исключительно добровольным, будьте честны с тем, сколько времени у вас есть. Это не то же самое, что количество времени, которое, по вашему мнению, требуется проекту, или количество времени, которое другие люди хотят, чтобы вы провели.

Вот несколько правил, которые стоит записать:

* Как участие рассматривается и принимается (_Им нужны тесты? Шаблон вопроса?_)
* Типы участия, которые вы принимаете (_Вам нужна только помощь с определенной частью вашего кода?_)
* Когда уместно отслеживание? (_например, «Вы можете ожидать ответа от сопровождающего в течение 7 дней. Если вы ничего не услышали к тому времени, не стесняйтесь пинговать поток."_)
* Сколько времени вы тратите на проект(_например, «Мы тратим около 5 часов в неделю на этот проект"_)

[Jekyll](https://github.com/jekyll/jekyll/tree/master/docs), [CocoaPods](https://github.com/CocoaPods/CocoaPods/wiki/Communication-&-Design-Rules), и [Homebrew](https://github.com/Homebrew/brew/blob/bbed7246bc5c5b7acb8c1d427d10b43e090dfd39/docs/Maintainers-Avoiding-Burnout.md) Несколько примеров проектов с основными правилами для сопровождающих и участников.

### Держите общение публичным

Не забудьте также документировать ваши взаимодействия. Везде, где можете, держать общение о вашем проекте публичным. Если кто-то попытается связаться с вами в частном порядке, чтобы обсудить запрос функции или необходимость поддержки, вежливо направьте их на общедоступный канал связи, такой как список рассылки или система отслеживания проблем.

Если вы встречаетесь с другими сопровождающими, или принимаете важное решение в частном порядке, документировать эти разговоры публично, даже если он просто публикует свои заметки.

Таким образом, любой, кто присоединится к вашему сообществу, будет иметь доступ к той же информации, что и тот, кто был там годами..

## Учимся говорить "нет"

Вы все записали. В идеале, каждый мог бы прочитать вашу документацию, но в действительности вам придется напоминать другим, что эти знания существуют.

Однако, все записанное помогает обезличить ситуации, когда вам нужно применять свои правила.

Говорить нет не весело, но  _"Ваш вклад не соответствует критериям этого проекта"_ чувствуется менее личным, чем _"Мне не нравится твой вклад"_.

Говорить «нет» относится ко многим ситуациям, с которыми вы столкнетесь как сопровождающий: запросы функций, которые не вписываются в рамки, кто-то срывает обсуждение, делает ненужную работу для других.

### Сохраняйте общение дружелюбным

Одно из самых важных мест, где вы будете практиковать: «Нет» - это ваша проблема и очередь запросов. Как сопровождающий проекта, вы неизбежно получите предложения, которые вы не хотите принимать.

Может быть, вклад меняет масштаб вашего проекта или не соответствует вашему видению. Может быть, идея хорошая, но реализация плохая.

Независимо от причины, можно тактично обрабатывать вклады, которые не соответствуют стандартам вашего проекта.

Если вы получаете участие, которое не хотите принимать, вашей первой реакцией может быть игнорирование или вид, что вы его не видели. Это может повредить чувствам другого человека и даже лишить мотивации других потенциальных участников в вашем сообществе.

<aside markdown="1" class="pquote">
  <img src="https://avatars.githubusercontent.com/krausefx?s=180" class="pquote-avatar" alt="avatar">
  Ключом к поддержке крупномасштабных проектов с открытым исходным кодом является поддержание проблем движении. Старайтесь избегать срыва проблем (issue). Если вы iOS разработчик вы знаете, как сложно представить радары. Вы могли бы вернуться 2 года спустя, и попробовать еще раз с последней версией iOS.
  <p markdown="1" class="pquote-credit">
— @KrauseFx, ["Масштабирование сообществ с открытым исходным кодом"](https://krausefx.com/blog/scaling-open-source-communities)
  </p>
</aside>

Не оставляйте нежелательный вклад открытым, из-за того что вы чувствуете вину или хотите быть милым. Со временем ваши оставшиеся без ответа вопросы и PR сделают работу над вашим проектом намного более напряженной и пугающей..

Лучше немедленно закрыть вклады, которые вы не хотите принимать. If your project already suffers from a large backlog, @steveklabnik has suggestions for [how to triage issues efficiently](https://words.steveklabnik.com/how-to-be-an-open-source-gardener).

Secondly, ignoring contributions sends a negative signal to your community. Contributing to a project can be intimidating, especially if it's someone's first time. Even if you don't accept their contribution, acknowledge the person behind it and thank them for their interest. It's a big compliment!

If you don't want to accept a contribution:

* **Thank them** for their contribution
* **Explain why it doesn't fit** into the scope of the project, and offer clear suggestions for improvement, if you're able. Be kind, but firm.
* **Link to relevant documentation**, if you have it. If you notice repeated requests for things you don't want to accept, add them into your documentation to avoid repeating yourself.
* **Close the request**

You shouldn't need more than 1-2 sentences to respond. For example, when a user of [celery](https://github.com/celery/celery/) reported a Windows-related error, @berkerpeksag [responded with](https://github.com/celery/celery/issues/3383):

![Celery screenshot](/assets/images/best-practices/celery.png)

If the thought of saying no terrifies you, you're not alone. As @jessfraz [put it](https://blog.jessfraz.com/post/the-art-of-closing/):

> I've talked to maintainers from several different open source projects, Mesos, Kubernetes, Chromium, and they all agree one of the hardest parts of being a maintainer is saying "No" to patches you don't want.

Don't feel guilty about not wanting to accept someone's contribution. The first rule of open source, [according to](https://twitter.com/solomonstre/status/715277134978113536) @shykes: _"No is temporary, yes is forever."_ While empathizing with another person's enthusiasm is a good thing, rejecting a contribution is not the same as rejecting the person behind it.

Ultimately, if a contribution isn't good enough, you're under no obligation to accept it. Be kind and responsive when people contribute to your project, but only accept changes that you truly believe will make your project better. The more often you practice saying no, the easier it becomes. Promise.

### Be proactive

To reduce the volume of unwanted contributions in the first place, explain your project's process for submitting and accepting contributions in your contributing guide.

If you're receiving too many low-quality contributions, require that contributors do a bit of work beforehand, for example:

* Fill out a issue or PR template/checklist
* Open an issue before submitting a PR

If they don't follow your rules, close the issue immediately and point to your documentation.

While this approach may feel unkind at first, being proactive is actually good for both parties. It reduces the chance that someone will put in many wasted hours of work into a pull request that you aren't going to accept. And it makes your workload easier to manage.

<aside markdown="1" class="pquote">
  <img src="https://avatars.githubusercontent.com/mikemcquaid?s=180" class="pquote-avatar" alt="avatar">
  Ideally, explain to them and in a CONTRIBUTING.md file how they can get a better indication in the future on what would or would not be accepted before they begin the work.
  <p markdown="1" class="pquote-credit">
— @MikeMcQuaid, ["Kindly Closing Pull Requests"](https://github.com/blog/2124-kindly-closing-pull-requests)
  </p>
</aside>

Sometimes, when you say no, your potential contributor may get upset or criticize your decision. If their behavior becomes hostile, [take steps to defuse the situation](https://github.com/jonschlinkert/maintainers-guide-to-staying-positive#action-items) or even remove them from your community, if they're not willing to collaborate constructively.

### Embrace mentorship

Maybe someone in your community regularly submits contributions that don't meet your project's standards. It can be frustrating for both parties to repeatedly go through rejections.

If you see that someone is enthusiastic about your project, but needs a bit of polish, be patient. Explain clearly in each situation why their contributions don't meet the expectations of the project. Try pointing them to an easier or less ambiguous task, like an issue marked _"good first issue,"_ to get their feet wet. If you have time, consider mentoring them through their first contribution, or find someone else in your community who might be willing to mentor them.

## Leverage your community

You don't have to do everything yourself. Your project's community exists for a reason! Even if you don't yet have an active contributor community, if you have a lot of users, put them to work.

### Share the workload

If you're looking for others to pitch in, start by asking around.

When you see new contributors making repeated contributions, recognize their work by offering more responsibility. Document how others can grow into leadership roles if they wish.

Encouraging others to [share ownership of the project](../building-community/#share-ownership-of-your-project) can greatly reduce your own workload, as @lmccart discovered on her project, [p5.js](https://github.com/processing/p5.js).

<aside markdown="1" class="pquote">
  <img src="https://avatars.githubusercontent.com/lmccart?s=180" class="pquote-avatar" alt="avatar">
  I’d been saying, "Yeah, anyone can be involved, you don’t have to have a lot of coding expertise [...]." We had people sign up to come [to an event] and that’s when I was really wondering: is this true, what I’ve been saying? There are gonna be 40 people who show up, and it’s not like I can sit with each of them...But people came together, and it just sort of worked. As soon as one person got it, they could teach their neighbor.
  <p markdown="1" class="pquote-credit">
—  @lmccart, ["What Does "Open Source" Even Mean? p5.js Edition"](https://medium.com/@kenjagan/what-does-open-source-even-mean-p5-js-edition-98c02d354b39)
  </p>
</aside>

If you need to step away from your project, either on hiatus or permanently, there's no shame in asking someone else to take over for you.

If other people are enthusiastic about its direction, give them commit access or formally hand over control to someone else. If someone forked your project and is actively maintaining it elsewhere, consider linking to the fork from your original project. It's great that so many people want your project to live on!

@progrium [found that](https://progrium.com/blog/2015/12/04/leadership-guilt-and-pull-requests/) documenting the vision for his project, [Dokku](https://github.com/dokku/dokku), helped those goals live on even after he stepped away from the project:

> I wrote a wiki page describing what I wanted and why I wanted it. For some reason it came as a surprise to me that the maintainers started moving the project in that direction! Did it happen exactly how I'd do it? Not always. But it still brought the project closer to what I wrote down.

### Let others build the solutions they need

If a potential contributor has a different opinion on what your project should do, you may want to gently encourage them to work on their own fork.

Forking a project doesn't have to be a bad thing. Being able to copy and modify projects is one of the best things about open source. Encouraging your community members to work on their own fork can provide the creative outlet they need, without conflicting with your project's vision.

<aside markdown="1" class="pquote">
  <img src="https://avatars.githubusercontent.com/geerlingguy?s=180" class="pquote-avatar" alt="avatar">
  I cater to the 80% use case. If you are one of the unicorns, please fork my work. I won't get offended! My public projects are almost always meant to solve the most common problems; I try to make it easy to go deeper by either forking my work or extending it.
  <p markdown="1" class="pquote-credit">
— @geerlingguy, ["Why I Close PRs"](https://www.jeffgeerling.com/blog/2016/why-i-close-prs-oss-project-maintainer-notes)
  </p>
</aside>

The same applies to a user who really wants a solution that you simply don't have the bandwidth to build. Offering APIs and customization hooks can help others meet their own needs, without having to modify the source directly. @orta [found that](https://artsy.github.io/blog/2016/07/03/handling-big-projects/) encouraging plugins for CocoaPods led to "some of the most interesting ideas":

> It's almost inevitable that once a project becomes big, maintainers have to become a lot more conservative about how they introduce new code. You become good at saying "no", but a lot of people have legitimate needs. So, instead you end up converting your tool into a platform.

## Bring in the robots

Just as there are tasks that other people can help you with, there are also tasks that no human should ever have to do. Robots are your friend. Use them to make your life as a maintainer easier.

### Require tests and other checks to improve the quality of your code

One of the most important ways you can automate your project is by adding tests.

Tests help contributors feel confident that they won't break anything. They also make it easier for you to review and accept contributions quickly. The more responsive you are, the more engaged your community can be.

Set up automatic tests that will run on all incoming contributions, and ensure that your tests can easily be run locally by contributors. Require that all code contributions pass your tests before they can be submitted. You'll help set a minimum standard of quality for all submissions. [Required status checks](https://help.github.com/articles/about-required-status-checks/) on GitHub can help ensure no change gets merged without your tests passing.

If you add tests, make sure to explain how they work in your CONTRIBUTING file.

<aside markdown="1" class="pquote">
  <img src="https://avatars.githubusercontent.com/edunham?s=180" class="pquote-avatar" alt="avatar">
  I believe that tests are necessary for all code that people work on. If the code was fully and perfectly correct, it wouldn't need changes – we only write code when something is wrong, whether that's "It crashes" or "It lacks such-and-such a feature". And regardless of the changes you're making, tests are essential for catching any regressions you might accidentally introduce.
  <p markdown="1" class="pquote-credit">
— @edunham, ["Rust's Community Automation"](https://edunham.net/2016/09/27/rust_s_community_automation.html)
  </p>
</aside>

### Use tools to automate basic maintenance tasks

The good news about maintaining a popular project is that other maintainers have probably faced similar issues and built a solution for it.

There are a [variety of tools available](https://github.com/showcases/tools-for-open-source) to help automate some aspects of maintenance work. A few examples:

* [semantic-release](https://github.com/semantic-release/semantic-release) automates your releases
* [mention-bot](https://github.com/facebook/mention-bot) mentions potential reviewers for pull requests
* [Danger](https://github.com/danger/danger) helps automate code review

For bug reports and other common contributions, GitHub has [Issue Templates and Pull Request Templates](https://github.com/blog/2111-issue-and-pull-request-templates), which you can create to streamline the communication you receive. @TalAter made a [Choose Your Own Adventure guide](https://www.talater.com/open-source-templates/#/) to help you write your issue and PR templates.

To manage your email notifications, you can set up [email filters](https://github.com/blog/2203-email-updates-about-your-own-activity) to organize by priority.

If you want to get a little more advanced, style guides and linters can standardize project contributions and make them easier to review and accept.

However, if your standards are too complicated, they can increase the barriers to contribution. Make sure you're only adding enough rules to make everyone's lives easier.

If you're not sure which tools to use, look at what other popular projects do, especially those in your ecosystem. For example, what does the contribution process look like for other Node modules? Using similar tools and approaches will also make your process more familiar to your target contributors.

## It's okay to hit pause

Open source work once brought you joy. Maybe now it's starting to make you feel avoidant or guilty.

Perhaps you're feeling overwhelmed or a growing sense of dread when you think about your projects. And meanwhile, the issues and pull requests pile up.

Burnout is a real and pervasive issue in open source work, especially among maintainers. As a maintainer, your happiness is a non-negotiable requirement for the survival of any open source project.

Although it should go without saying, take a break! You shouldn't have to wait until you feel burned out to take a vacation. @brettcannon, a Python core developer, decided to take [a month-long vacation](https://snarky.ca/why-i-took-october-off-from-oss-volunteering/) after 14 years of volunteer OSS work.

Just like any other type of work, taking regular breaks will keep you refreshed, happy, and excited about your work.

<aside markdown="1" class="pquote">
  <img src="https://avatars.githubusercontent.com/danielbachhuber?s=180" class="pquote-avatar" alt="avatar">
  In maintaining WP-CLI, I've discovered I need to make myself happy first, and set clear boundaries on my involvement. The best balance I've found is 2-5 hours per week, as a part of my normal work schedule. This keeps my involvement a passion, and from feeling too much like work. Because I prioritize the issues I'm working on, I can make regular progress on what I think is most important.
  <p markdown="1" class="pquote-credit">
— @danielbachhuber, ["My condolences, you're now the maintainer of a popular open source project"](https://runcommand.io/2016/06/26/my-condolences-youre-now-the-maintainer-of-a-popular-open-source-project/)
  </p>
</aside>

Sometimes, it can be hard to take a break from open source work when it feels like everybody needs you. People may even try to make you feel guilty for stepping away.

Do your best to find support for your users and community while you're away from a project. If you can't find the support you need, take a break anyway. Be sure to communicate when you're not available, so people aren't confused by your lack of responsiveness.

Taking breaks applies to more than just vacations, too. If you don't want to do open source work on weekends, or during work hours, communicate those expectations to others, so they know not to bother you.

## Take care of yourself first!

Maintaining a popular project requires different skills than the earlier stages of growth, but it's no less rewarding. As a maintainer, you'll practice leadership and personal skills on a level that few people get to experience. While it's not always easy to manage, setting clear boundaries and only taking on what you're comfortable with will help you stay happy, refreshed, and productive.
