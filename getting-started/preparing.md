---
title: Preparing for launch
next: marketing/index.md
---

You’re almost ready to launch your project! In this section, we’ll talk about what to include in an open source project before releasing it to the world.

Every open source project should include the following:

* License
* README
* Contributing guide
* Code of conduct

As a maintainer, these components will help you communicate expectations, manage contributions, protect your legal rights, and make sure that you and your contributors have a positive experience. The more you can document for your readers up front, the less work you’ll have to do later on.

## Choosing a license

An open source license guarantees that others can use, copy, modify and contribute back to your project without repercussions. It also protects you from any sticky legal situations.

Legal work is no fun. The good news is there are many licenses available that you can copy and paste into your repository. It will only take a minute to protect your hard work.

There are [over 70 approved licenses](https://opensource.org/licenses/alphabetical) that comply with the generally accepted definition of open source. Some licenses you’ll commonly hear about are:

* [MIT License](http://choosealicense.com/licenses/mit/)
* [Apache License 2.0](http://choosealicense.com/licenses/apache-2.0/)
* [Mozilla Public License 2.0](http://choosealicense.com/licenses/mpl-2.0/)
* [GNU General Public License v3.0](http://choosealicense.com/licenses/gpl-3.0/)

When you create a new project on GitHub, you are given the option to select a license. Including one of these licenses will make your GitHub project open source. (Different licenses carry slightly different permissions. You can use [http://choosealicense.com](http://choosealicense.com) to find the right license for you.)

If you have other questions or concerns around the legal aspects of managing an open source project, we've got you covered: [The legal side of open source](../legal/)

**(include image of license selection on GitHub new repo here?)**

## Writing a README

Your project’s README file gives your reader context about the project.

The README should do more than explain how to use your project. It should also help your audience understand why the project is useful and what they can do with it.

In your README, try to answer the following questions:

* What does the project do?
* As a user, how does this project help me?
* How do I get started?
* Where can I get more help, if I need it?

You can also use your README to answer other questions, like how you handle contributions, what the goals of the project are, and information about licenses and attribution.

Sometimes, people avoid writing a README because they feel like the project is unfinished, or they don’t want contributions. These are all very good reasons to write one.

As a maintainer, READMEs are an opportunity to clarify your goals in public. If you don’t want to accept contributions or your project is not yet ready for production, you should especially write this information down. That way, people understand your needs as soon as they arrive at your project.

When you include a README file in the root directory, GitHub will automatically display it on your project repository’s homepage. It will be the first thing someone sees when they arrive.

## Setting your contributing guidelines

A CONTRIBUTING file tells your audience how to participate in your project. For example, you might want to tell your reader how to create an issue, file a bug report, test fixes, or format code.

In addition to technical details, a CONTRIBUTING file is an opportunity to communicate your expectations for contributions. Remember that no two open source projects are alike. Write down rules that work best for you and your lifestyle. For example, you may want to convey that you are only accepting certain types of contributions, tell participants how long they should expect to hear a response from you, or explain how (or how not) to get in touch with you.

If you are a community project, you can use the CONTRIBUTING file to actively solicit the types of contributions you’re looking for. Using a warm, friendly tone and offering specific contribution suggestions (such as writing documentation, or making a website) can go a long way in making newcomers feel welcomed and excited to participate.

You should reference your CONTRIBUTING file in your README. In your README, give your audience a quick overview of how contributions work, then link to the CONTRIBUTING file for more information.

If you place your CONTRIBUTING file in the root directory, GitHub will automatically link to your file when a contributor creates an issue or opens a pull request.

## Writing a code of conduct

Finally, a code of conduct helps set ground rules for communication among your project’s participants. The [Django Code of Conduct](https://www.djangoproject.com/conduct/) and the [Angular Code of Conduct](https://github.com/angular/code-of-conduct/blob/master/CODE_OF_CONDUCT.md) are two good examples.

A code of conduct is a place to convey the values or philosophy that define your project. This is especially valuable if you’re a community or company launching an open source project.

Codes of conduct help protect not just your participants, but yourself. As you maintain your project, you may find that unproductive attitudes from other participants can make you feel drained or unhappy about your work. A code of conduct empowers you to facilitate healthy, constructive community behavior. Being proactive about these expectations reduces the likelihood that you, or others, will become fatigued with your project later on. You can read more about enforcing codes of conduct [here](../../troubleshooting/conduct/).

In addition to communicating your expectations, you should describe what happens if someone violates the code of conduct, and where someone can report such behavior. We recommend placing a CODE_OF_CONDUCT file in your root directory.

## What’s next?

Now that you have these four files in the root directory of your project, you’re ready to open source your project! Click "publish" and pat yourself on the back. Then continue on to the next section. We’ve got work to do.

Launching your project is only the first step. If you’re hoping people will discover and use your project, you’ll want to make sure other people know about it.

Sometimes, it will take a long time before people notice your open source project. Your project will likely go through multiple phases of activity and contributorship. That’s okay! Some of the most popular projects today took years to reach high levels of activity. The rest of this handbook is designed to help you manage your project every step of the way.

### Further reading

* Licenses
  * [https://github.com/blog/1530-choosing-an-open-source-license](https://github.com/blog/1530-choosing-an-open-source-license)
  * [http://choosealicense.com](http://choosealicense.com)
* READMEs
  * [http://tom.preston-werner.com/2010/08/23/readme-driven-development.html](http://tom.preston-werner.com/2010/08/23/readme-driven-development.html)
  * [https://github.com/matiassingers/awesome-readme](https://github.com/matiassingers/awesome-readme)
  * [https://pages.18f.gov/open-source-guide/making-readmes-readable/](https://pages.18f.gov/open-source-guide/making-readmes-readable/)
  * [https://changelog.com/a-beginners-guide-to-creating-a-readme/](https://changelog.com/a-beginners-guide-to-creating-a-readme/)
  * [https://gist.github.com/jxson/1784669](https://gist.github.com/jxson/1784669)
* Contributing guides
  * [https://github.com/blog/1184-contributing-guidelines](https://github.com/blog/1184-contributing-guidelines)
  * [http://www.contribution-guide.org/](http://www.contribution-guide.org/)
  * [https://github.com/nayafia/contributing-template](https://github.com/nayafia/contributing-template)
  * [http://mozillascience.github.io/working-open-workshop/contributing/](http://mozillascience.github.io/working-open-workshop/contributing/)
* Codes of conduct
  * [http://contributor-covenant.org/](http://contributor-covenant.org/)
  * [https://github.com/django/code-of-conduct](https://github.com/django/code-of-conduct)
  * [https://adainitiative.org/2014/02/18/howto-design-a-code-of-conduct-for-your-community/](https://adainitiative.org/2014/02/18/howto-design-a-code-of-conduct-for-your-community/)
  * [https://github.com/docker/docker/blob/master/CONTRIBUTING.md#docker-community-guidelines/](https://github.com/docker/docker/blob/master/CONTRIBUTING.md#docker-community-guidelines/)