# Moe-Counter

多种风格可选的萌萌计数器

![Moe-Counter](https://count.getloli.com/@Moe-counter.github)

<details>
<summary>More theme</summary>

### *[Contribute themes is welcome!](https://github.com/journey-ad/Moe-Counter/issues/new?assignees=&labels=theme&projects=&template=contribute-theme.yml&title=%5BTheme%5D%3A+)*

##### asoul

![asoul](https://count.getloli.com/@demo?theme=asoul)

##### booru-ffsr

![booru-ffsr](https://count.getloli.com/@demo?theme=booru-ffsr)

##### booru-helltaker

![booru-helltaker](https://count.getloli.com/@demo?theme=booru-helltaker)

##### booru-huggboo

![booru-huggboo](https://count.getloli.com/@demo?theme=booru-huggboo)

##### booru-jaypee

![booru-jaypee](https://count.getloli.com/@demo?theme=booru-jaypee)

##### booru-koe

![booru-koe](https://count.getloli.com/@demo?theme=booru-koe)

##### booru-lisu

![booru-lisu](https://count.getloli.com/@demo?theme=booru-lisu)

##### booru-mjg

![booru-mjg](https://count.getloli.com/@demo?theme=booru-mjg)

##### booru-mof

![booru-mof](https://count.getloli.com/@demo?theme=booru-mof)

##### booru-nandroid

![booru-nandroid](https://count.getloli.com/@demo?theme=booru-nandroid)

##### booru-qualityhentais

![booru-qualityhentais](https://count.getloli.com/@demo?theme=booru-qualityhentais)

##### booru-r6gdrawfriends

![booru-r6gdrawfriends](https://count.getloli.com/@demo?theme=booru-r6gdrawfriends)

##### booru-rfck

![booru-rfck](https://count.getloli.com/@demo?theme=booru-rfck)

##### booru-smtg

![booru-smtg](https://count.getloli.com/@demo?theme=booru-smtg)

##### booru-snyde

![booru-snyde](https://count.getloli.com/@demo?theme=booru-snyde)

##### booru-the-collection

![booru-the-collection](https://count.getloli.com/@demo?theme=booru-the-collection)

##### booru-touhoulat

![booru-touhoulat](https://count.getloli.com/@demo?theme=booru-touhoulat)

##### booru-townofgravityfalls

![booru-townofgravityfalls](https://count.getloli.com/@demo?theme=booru-townofgravityfalls)

##### booru-twifanartsfw

![booru-twifanartsfw](https://count.getloli.com/@demo?theme=booru-twifanartsfw)

##### booru-ve

![booru-ve](https://count.getloli.com/@demo?theme=booru-ve)

##### booru-vivi

![booru-vivi](https://count.getloli.com/@demo?theme=booru-vivi)

##### booru-vp

![booru-vp](https://count.getloli.com/@demo?theme=booru-vp)

##### booru-yuyuyui

![booru-yuyuyui](https://count.getloli.com/@demo?theme=booru-yuyuyui)

##### e621

![e621](https://count.getloli.com/@demo?theme=e621)

##### gelbooru

![gelbooru](https://count.getloli.com/@demo?theme=gelbooru)

##### green

![green](https://count.getloli.com/@demo?theme=green)

##### kasuterura-1

![kasuterura-1](https://count.getloli.com/@demo?theme=kasuterura-1)

##### kasuterura-2

![kasuterura-2](https://count.getloli.com/@demo?theme=kasuterura-2)

##### kasuterura-3

![kasuterura-3](https://count.getloli.com/@demo?theme=kasuterura-3)

##### kasuterura-4

![kasuterura-4](https://count.getloli.com/@demo?theme=kasuterura-4)

##### kyun

![kyun](https://count.getloli.com/@demo?theme=kyun)

##### minecraft

![minecraft](https://count.getloli.com/@demo?theme=minecraft)

##### moebooru

![moebooru](https://count.getloli.com/@demo?theme=moebooru)

##### nixietube-1

![nixietube-1](https://count.getloli.com/@demo?theme=nixietube-1)

##### nixietube-2

![nixietube-2](https://count.getloli.com/@demo?theme=nixietube-2)

##### normal-1

![normal-1](https://count.getloli.com/@demo?theme=normal-1)

##### normal-2

![normal-2](https://count.getloli.com/@demo?theme=normal-2)

##### original-new

![original-new](https://count.getloli.com/@demo?theme=original-new)

##### original-old

![original-old](https://count.getloli.com/@demo?theme=original-old)

##### rule34

![rule34](https://count.getloli.com/@demo?theme=rule34)

##### shimmie2

![shimmie2](https://count.getloli.com/@demo?theme=shimmie2)

</details>

## Demo
[https://count.getloli.com](https://count.getloli.com)

## How to use

About the counter usage, please see the [website homepage](https://count.getloli.com).

## Usage

### Install

#### Run on Glitch

- Open [Glitch project](https://glitch.com/~moe-counter-api)
- Just hit the **Remix your own** button
- That's it!

#### Deploying on your own server

```shell
$ git clone https://github.com/journey-ad/Moe-Counter.git
$ cd Moe-Counter
$ pnpm install

$ pnpm run start
```

### Configuration

`config.yml`

```yaml
app:
  # site: https://count.getloli.com # your website
  port: 3000

db:
  type: sqlite # sqlite or mongodb
  interval: 60 # write to db interval in seconds (0 for realtime)
```

If using mongodb, you need to specify the environment variable `DB_URL`

```shell
# e.g.
export DB_URL=mongodb+srv://account:passwd@***.***.***.mongodb.net/db_count
```

Glitch can use `.env` file, [documentation](https://help.glitch.com/hc/en-us/articles/16287550167437-Adding-Private-Data)

## Credits

* [Glitch](https://glitch.com/)
* [A-SOUL_Official](https://space.bilibili.com/703007996)
* [moebooru](https://github.com/moebooru/moebooru)
* rule34.xxx NSFW
* gelbooru.com NSFW
* [Icons8](https://icons8.com/icon/80355/star)

## License

[MIT License](./LICENSE), excluding all themes
