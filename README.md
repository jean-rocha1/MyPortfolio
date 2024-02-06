<h1 align="center">Welcome to my develper-ortfolio 👋</h1>
<a href="https://github.com/1hanzla100/developer-portfolio/blob/main/LICENSE"><img alt="GitHub license" src="https://img.shields.io/github/license/1hanzla100/developer-portfolio"></a><a href="https://github.com/1hanzla100/developer-portfolio/issues"><img alt="GitHub issues" src="https://img.shields.io/github/issues/1hanzla100/developer-portfolio"></a><a href="https://github.com/1hanzla100/developer-portfolio/network"><img alt="GitHub forks" src="https://img.shields.io/github/forks/1hanzla100/developer-portfolio"></a> <a href="https://github.com/1hanzla100/developer-portfolio/stargazers"><img alt="GitHub stars" src="https://img.shields.io/github/stars/1hanzla100/developer-portfolio"></a>

<h2 align = "center">  Unveiling Stories through Data Analysis and Low-Code App Development for Everyday Ease. 

<p align="center">
  <kbd>
    <img src="https://github.com/jean-rocha1/MyPortfolio/blob/main/Group%20112.png"></img>
  </kbd>
</p>

## Projetos, **[click here](https://developer-portfolio-1hanzla100.vercel.app/)**.

## Square Analysis, **[click here](https://app.powerbi.com/reportEmbed?reportId=fc7abf58-d2d1-4802-9bfc-ccd80abb21ad&autoAuth=true&ctid=30cb66b6-2919-4c93-b208-6b8e8cefdd39/)**.
This project enables users to accurately determine the distance between a selected school and nearby schools. The information provided includes the number of pupils in each school, their locations, and the average ticket price. This allows for a comprehensive and effortless comparison of schools within a specific radius. 

<p align="center">
  <kbd>
    <img src="https://github.com/jean-rocha1/MyPortfolio/blob/main/Design%20sem%20nome.gif"></img>
  </kbd>
</p>

```Dax
Principal Dax = 
VAR Rad_lat1 =
    SELECTEDVALUE ( Origem[Latitude] ) / 57.2957795
VAR Rad_lat2 =
    SELECTEDVALUE ( Fat_Organization[Latitude] ) / 57.2957795
VAR Rad_long1 =
    SELECTEDVALUE ( Origem[Longitude] ) / 57.2957795
VAR Rad_long2 =
    SELECTEDVALUE ( Fat_Organization[Longitude] ) / 57.2957795
VAR x =
    ROUND (
        SIN ( Rad_lat1 ) * SIN ( Rad_lat2 )
            + COS ( Rad_lat1 ) * COS ( Rad_lat2 )
                * COS ( Rad_long1 - Rad_long2 ),
        15
    )
VAR vTerra = 6371
RETURN
    ACOS ( x ) * 6371

````
## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing
purposes.

You'll need [Git](https://git-scm.com) and [Node.js](https://nodejs.org/en/download/) (which comes with
[npm](http://npmjs.com)) installed on your computer. <br> **For Windows** Install Visual C++ Build Environment:
[Visual Studio Build Tools](https://visualstudio.microsoft.com/thank-you-downloading-visual-studio/?sku=BuildTools)

```
node@v10.16.0 or higher
npm@6.9.0 or higher
git@2.17.1 or higher
```

## How To Use

1. Fork this repoistory and clone it to your local machine.

```bash
$ git clone https://github.com/<your-username>/developer-portfolio.git
```

2. Go into the repository

```bash
$ cd developer-portfolio
```

3. Install dependencies

```bash
$ yarn
```

4. Edit `portfolio.js`

5. Start your development server

```bash
$ yarn dev
```

## Linking Portfolio to Github

```javascript
  //  portfolio.js
  githubUserName: 'YOUR GITHUB USERNAME HERE',
```

#### Using Emojis

For adding emoji 😃 into the texts in `Portfolio.js`, use the `emoji()` function and pass the text you need as an
argument. This would help in keeping emojis compatible across different browsers and platforms.

## Technologies Used

- [Next.js](https://nextjs.org/)
- [axios](https://www.npmjs.com/package/axios)
- [reactstrap](https://reactstrap.github.io/)
- [react-reveal](https://www.react-reveal.com/)
- [react-lottie](https://www.npmjs.com/package/react-lottie)
- [react-easy-emoji](https://github.com/appfigures/react-easy-emoji)
- [react-headroom](https://github.com/KyleAMathews/react-headroom)
- [color-thief](https://github.com/lokesh/color-thief)

## Illustrations

- [Lottie File Source](https://lottiefiles.com)

## Icons

Iconify Icons are used in skill section. You can find all the icons here: [Iconify](https://icon-sets.iconify.design/).

## For the Future

If you can help us with these. Please don't hesitate to open a
[pull request](https://github.com/1hanzla100/developer-portfolio/pulls).

- Enable Dark Mode

- Add More Sections

## Author

👤 **Hanzla Tauqeer**

- Website: https://hanzla.netlify.app
- Github: [@1hanzla100](https://github.com/1hanzla100)
- LinkedIn: [@1hanzla100](https://linkedin.com/in/1hanzla100)

## Show your support

Give a ⭐️ if this project helped you!
