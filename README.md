<div align="center">
<h1>Ashish's Code Challenge</h1>

[![Project Status: WIP – Initial development is in progress, but there has not yet been a stable, usable release suitable for the public.](https://www.repostatus.org/badges/latest/wip.svg)](https://www.repostatus.org/#wip)

<p>Ashish's code challenge: Helping developers to be productive on current pandemic situation.</p>

</div>

## Table of Contents

- [What is Ashish's Code Challenge?](#what-is-ashishs-code-challenge)
- [Eligibility](#eligibility)
- [How can I participate?](#how-can-i-participate)
  - [Requirements](#requirements)
- [Submissions](#submissions)
  - [Make a pull request](#make-a-pull-request)
- [FAQ](#faq)

## What is Ashish's Code Challenge?

Ashish's code challenge is a simple initiative to make the developers more productive during this lockdown period. I believe by participating, it can help you to develop your skills & also improve your portfolio.

This challenge will provide specific task ( not a whole project ) which can be implemented in most of the projects or you can make a complete whole project.

Maybe someone might come up with a great idea after trying few challenges? Who knows?

## Eligibility

Any developer with any level of expertise.

## How can I participate?

To participate in this challenge, there are few requirements to be followed but can be ignored completely if you just want to try the challenge. Please check below.

### Requirements

- Your project must be hosted on GitHub as a public repository.
- Your Readme file must include hashtag `#ashish-code-challenge` in the description.
- A clear screenshot of the demo. Check the `acc-info.json` sample file below.
- Make a [Pull Request](#make-a-pull-request) to get featured in GH page of this repository.

## Submissions

Submit your project to this repository to showcase & get featured in th GH Page. Your project might follow the best standard which can help others? Isn't it?

## Make a pull request

Once you've develop & tested (optional) your project, you can share it on Ashish's Code Challenge.

If your project doesn't have a `package.json` or `manifest.json` file, You should include the file below in root folder.

| File          | Purpose                                                                   |
| ------------- | ------------------------------------------------------------------------- |
| acc-info.json | Contains metadata of your project. Check the [sample file](#sample-file). |

First, [fork](https://guides.github.com/activities/forking/) this repository.

Create a branch.

Create a folder with same name as your username inside `submissions` folder.

All your projects for different challenge should be inside your `username` folder.

Example structure:

```
│   LICENSE
│   README.md
│
├───challenges
└───submissions
    └───ashiishme
        ├───challenge-001
        ├───challenge-002
        ├───challenge-003
        └───challenge-004
```

[Shallow clone](https://git-scm.com/docs/git-clone#Documentation/git-clone.txt---depthltdepthgt) your repository inside your username folder.

```
git clone --depth=1 <your-own-repository-url>
```

Add a `acc-info.json` file in your project.

#### Sample file:

`acc-info.json`:

```json
{
  "name": "Ashish's Code Challenge",
  "version": "0.1.0",
  "description": "Ashish's code challenge: Helping developers to be productive on current pandemic situation.",
  "author": "Ashish Yadav",
  "author_uri": "https://github.com/ashiishme",
  "repository_uri": "https://github.com/ashiishme/ashish-code-challenge.git",
  "license": "MIT",
  "license_uri": "https://github.com/ashiishme/ashish-code-challenge/blob/master/LICENSE",
  "tags": ["code challenge"]
}
```

commit the changes and push to your fork.

Open a PR in Ashish's code challenge.

## FAQ

#### I am a beginner, Can I participate?

Yes, check the [eligibility](#eligibility) section.

#### Is it worth to participate in this challenge?

I believe, doing self project is really hard but if you are challenged to do something in a specific time, you will be more dedicated. So, yes it is worth to participate to make yourself more productive and get some project on your portfolio list.

#### What happens to the project? Will you sell them?

No. The project ideas will be very simple and available through this repository. They are always open-sourced & free to use.

#### Is it necessary to submit PR?

No, if you submit PR and gets merged then, it will be listed on the showcase page.

#### When will Ashish's code challenge end?

As long as the developers are interested to complete the challenge. It will not end.

#### Should I follow the best practices & standards?

If possible, Yes but you can do free-style or just on your own way.

#### Will I get paid after completing the challenge?

No, the idea behind this challenge is to make you more productive.
