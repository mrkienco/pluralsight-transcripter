# Pluralsight Video Transcripter 
Translate your offline videos to your preference language.

![Pluralsight](https://rawcdn.githack.com/giansalex/pluralsight-transcripter/500eea4d2f34e5549493b7ab065751d2bdd852dc/main.ico)

# Use
Install from [chocolatey.org](https://chocolatey.org/packages/pluralsight-transcripter/).
```
choco install pluralsight-transcripter
```
Also, you cand download from [releases](https://github.com/giansalex/pluralsight-transcripter/releases) or build from [source code](https://github.com/giansalex/pluralsight-transcripter/blob/master/CONTRIBUTING.md).

> Required pluralsight sqlite path, you can search in `%appdata%\..\Local\Pluralsight` 

```
transcripter --lang es pluralsight.db
```
This generate `pluralsight.es.db` in current directory, then you can override original database
