<!-- markdownlint-disable -->
<h1 align="center">
    best-of-scala
    <br>
</h1>

<p align="center">
    <strong>🏆&nbsp; A ranked list of awesome Scala open-source libraries & tools. Updated weekly.</strong>
</p>

<p align="center">
    <a href="https://best-of.org" title="Best-of Badge"><img src="http://bit.ly/3o3EHNN"></a>
    <a href="#Contents" title="Project Count"><img src="https://img.shields.io/badge/projects-22-blue.svg?color=5ac4bf"></a>
    <a href="#Contribution" title="Contributions are welcome"><img src="https://img.shields.io/badge/contributions-welcome-green.svg"></a>
    <a href="https://github.com/stkeky/best-of-scala/releases" title="Best-of Updates"><img src="https://img.shields.io/github/release-date/stkeky/best-of-scala?color=green&label=updated"></a>
</p>

This curated list contains 22 awesome open-source projects with a total of 15K stars grouped into 4 categories. All projects are ranked by a project-quality score, which is calculated based on various metrics automatically collected from GitHub and different package managers. If you like to add or update projects, feel free to open an [issue](https://github.com/stkeky/best-of-scala/issues/new/choose), submit a [pull request](https://github.com/stkeky/best-of-scala/pulls), or directly edit the [projects.yaml](https://github.com/stkeky/best-of-scala/edit/main/projects.yaml). Contributions are very welcome!

> 🧙‍♂️  Discover other [best-of lists](https://best-of.org) or [create your own](https://github.com/best-of-lists/best-of/blob/main/create-best-of-list.md).

## Contents

- [Miscelaneous](#miscelaneous) _2 projects_
- [Database Clients](#database-clients) _3 projects_
- [Ecosystems](#ecosystems) _1 projects_
- [JSON](#json) _16 projects_

## Explanation
- 🥇🥈🥉&nbsp; Combined project-quality score
- ⭐️&nbsp; Star count from GitHub
- 🐣&nbsp; New project _(less than 6 months old)_
- 💤&nbsp; Inactive project _(6 months no activity)_
- 💀&nbsp; Dead project _(12 months no activity)_
- 📈📉&nbsp; Project is trending up or down
- ➕&nbsp; Project was recently added
- ❗️&nbsp; Warning _(e.g. missing/risky license)_
- 👨‍💻&nbsp; Contributors count from GitHub
- 🔀&nbsp; Fork count from GitHub
- 📋&nbsp; Issue count from GitHub
- ⏱️&nbsp; Last update timestamp on package manager
- 📥&nbsp; Download count from package manager
- 📦&nbsp; Number of dependent projects
- <img src="https://zio.dev/img/navbar_brand.png" style="display:inline;" width="13" height="13">&nbsp; Type-safe, composable asynchronous and concurrent programming for Scala.

<br>

## Miscelaneous

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Miscelaneous projects that currently don't fit into any other category._

<details><summary><b><a href="https://github.com/lambdaworks/scountries">scountries</a></b> (🥇9 ·  ⭐ 17 · 🐣) - Scala library that provides an enumeration of ISO 3166 codes.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/lambdaworks/scountries) (👨‍💻 3 · 🔀 1 · ⏱️ 09.03.2023):

	```
	git clone https://github.com/lambdaworks/scountries
	```
- [Maven](https://search.maven.org/artifact/io.lambdaworks/scountries):
	```
	<dependency>
		<groupId>io.lambdaworks</groupId>
		<artifactId>scountries</artifactId>
		<version>[VERSION]</version>
	</dependency>
	```
</details>
<details><summary><b><a href="https://github.com/lambdaworks/scurl-detector">scurl-detector</a></b> (🥇9 ·  ⭐ 15) - Scala library that detects and extracts URLs from text. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/lambdaworks/scurl-detector) (👨‍💻 5 · 🔀 1 · 📋 10 - 10% open · ⏱️ 01.02.2023):

	```
	git clone https://github.com/lambdaworks/scurl-detector
	```
- [Maven](https://search.maven.org/artifact/io.lambdaworks/scurl-detector):
	```
	<dependency>
		<groupId>io.lambdaworks</groupId>
		<artifactId>scurl-detector</artifactId>
		<version>[VERSION]</version>
	</dependency>
	```
</details>
<br>

## Database Clients

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for connecting to, operating, and querying databases._

<details><summary><b><a href="https://github.com/sksamuel/elastic4s">elastic4s</a></b> (🥇25 ·  ⭐ 1.6K) - Elasticsearch Scala Client - Reactive, Non Blocking, Type Safe,.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/sksamuel/elastic4s) (👨‍💻 390 · 🔀 670 · 📋 1.1K - 2% open · ⏱️ 25.01.2023):

	```
	git clone https://github.com/sksamuel/elastic4s
	```
- [Maven](https://search.maven.org/artifact/com.sksamuel.elastic4s/elastic4s):
	```
	<dependency>
		<groupId>com.sksamuel.elastic4s</groupId>
		<artifactId>elastic4s</artifactId>
		<version>[VERSION]</version>
	</dependency>
	```
</details>
<details><summary><b><a href="https://github.com/scalikejdbc/scalikejdbc">scalikejdbc</a></b> (🥉22 ·  ⭐ 1.2K) - A tidy SQL-based DB access library for Scala developers. This.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/scalikejdbc/scalikejdbc) (👨‍💻 100 · 🔀 220 · 📋 480 - 5% open · ⏱️ 12.03.2023):

	```
	git clone https://github.com/scalikejdbc/scalikejdbc
	```
- [Maven](https://search.maven.org/artifact/org.scalikejdbc/scalikejdbc):
	```
	<dependency>
		<groupId>org.scalikejdbc</groupId>
		<artifactId>scalikejdbc</artifactId>
		<version>[VERSION]</version>
	</dependency>
	```
</details>
<details><summary><b><a href="https://github.com/lambdaworks/zio-elasticsearch">zio-elasticsearch</a></b> (🥉11 ·  ⭐ 40) - ZIO Elasticsearch is a type-safe, testable and.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://zio.dev/img/navbar_brand.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/lambdaworks/zio-elasticsearch) (👨‍💻 7 · 🔀 4 · 📋 19 - 73% open · ⏱️ 15.03.2023):

	```
	git clone https://github.com/lambdaworks/zio-elasticsearch
	```
- [Maven](https://search.maven.org/artifact/lambdaworks.io/zio-elasticsearch):
	```
	<dependency>
		<groupId>lambdaworks.io</groupId>
		<artifactId>zio-elasticsearch</artifactId>
		<version>[VERSION]</version>
	</dependency>
	```
</details>
<br>

## Ecosystems

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Extensions and platforms that provides various abstractions._

<details><summary><b><a href="https://github.com/zio/zio">zio</a></b> (🥇27 ·  ⭐ 3.7K · 📉) - ZIO A type-safe, composable library for async and concurrent.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/zio/zio) (👨‍💻 640 · 🔀 1.1K · 📋 2.3K - 15% open · ⏱️ 15.03.2023):

	```
	git clone https://github.com/zio/zio
	```
- [Maven](https://search.maven.org/artifact/dev.zio/zio):
	```
	<dependency>
		<groupId>dev.zio</groupId>
		<artifactId>zio</artifactId>
		<version>[VERSION]</version>
	</dependency>
	```
</details>
<br>

## JSON

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries that handles JSON format._

<details><summary><b><a href="https://github.com/circe/circe">circe</a></b> (🥇24 ·  ⭐ 2.4K · ➕) - Yet another JSON library for Scala. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/circe/circe) (👨‍💻 260 · 🔀 510 · 📋 510 - 31% open · ⏱️ 15.03.2023):

	```
	git clone https://github.com/travisbrown/circe
	```
- [Maven](https://search.maven.org/artifact/io.circe/circe-core):
	```
	<dependency>
		<groupId>io.circe</groupId>
		<artifactId>circe-core</artifactId>
		<version>[VERSION]</version>
	</dependency>
	```
</details>
<details><summary><b><a href="https://github.com/json4s/json4s">json4s</a></b> (🥇20 ·  ⭐ 1.4K · ➕) - JSON library. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/json4s/json4s) (👨‍💻 130 · 🔀 320 · 📋 400 - 36% open · ⏱️ 10.03.2023):

	```
	git clone https://github.com/json4s/json4s
	```
</details>
<details><summary><b><a href="https://github.com/plokhotnyuk/jsoniter-scala">jsoniter-scala</a></b> (🥇20 ·  ⭐ 620 · ➕) - Scala macros for compile-time generation of safe and ultra-.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/plokhotnyuk/jsoniter-scala) (👨‍💻 17 · 🔀 75 · 📦 1 · 📋 260 - 20% open · ⏱️ 12.03.2023):

	```
	git clone https://github.com/plokhotnyuk/jsoniter-scala
	```
</details>
<details><summary><b><a href="https://github.com/zio/zio-json">zio-json</a></b> (🥇20 ·  ⭐ 370 · ➕) - Fast, secure JSON library with tight ZIO integration. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://zio.dev/img/navbar_brand.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/zio/zio-json) (👨‍💻 51 · 🔀 110 · 📋 140 - 42% open · ⏱️ 13.03.2023):

	```
	git clone https://github.com/zio/zio-json
	```
</details>
<details><summary><b><a href="https://github.com/playframework/play-json">play-json</a></b> (🥇20 ·  ⭐ 340 · ➕) - The Play JSON library. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/playframework/play-json) (👨‍💻 62 · 🔀 130 · 📋 110 - 33% open · ⏱️ 09.03.2023):

	```
	git clone https://github.com/playframework/play-json
	```
</details>
<details><summary><b><a href="https://github.com/FasterXML/jackson-module-scala">jackson-module-scala</a></b> (🥈18 ·  ⭐ 480 · ➕) - Add-on module for Jackson.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/FasterXML/jackson-module-scala) (👨‍💻 58 · 🔀 130 · 📋 440 - 9% open · ⏱️ 14.03.2023):

	```
	git clone https://github.com/FasterXML/jackson-module-scala
	```
</details>
<details><summary><b><a href="https://github.com/gnieh/diffson">diffson</a></b> (🥈18 ·  ⭐ 300 · ➕) - A scala diff/patch library for Json. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/gnieh/diffson) (👨‍💻 30 · 🔀 48 · 📋 48 - 10% open · ⏱️ 02.03.2023):

	```
	git clone https://github.com/gnieh/diffson
	```
</details>
<details><summary><b><a href="https://github.com/sirthias/borer">borer</a></b> (🥉12 ·  ⭐ 190 · ➕) - Efficient CBOR and JSON (de)serialization in Scala. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code></summary>

- [GitHub](https://github.com/sirthias/borer) (👨‍💻 8 · 🔀 12 · 📋 110 - 4% open · ⏱️ 09.02.2023):

	```
	git clone https://github.com/sirthias/borer
	```
</details>
<details><summary><b><a href="https://github.com/gzoller/ScalaJack">ScalaJack</a></b> (🥉10 ·  ⭐ 110 · ➕) - Fast JSON parser/generator for Scala. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/gzoller/ScalaJack) (👨‍💻 13 · 🔀 8 · 📋 51 - 3% open · ⏱️ 15.11.2022):

	```
	git clone https://github.com/gzoller/ScalaJack
	```
</details>
<details><summary><b><a href="https://github.com/nrktkt/ninny-json">ninny-json</a></b> (🥉8 ·  ⭐ 20 · ➕) - JSON typeclasses that know the difference between null and.. <code><a href="http://bit.ly/3rvuUlR">Unlicense</a></code></summary>

- [GitHub](https://github.com/nrktkt/ninny-json) (👨‍💻 2 · 🔀 4 · 📋 7 - 57% open · ⏱️ 12.01.2023):

	```
	git clone https://github.com/nrktkt/ninny-json
	```
</details>
<details><summary>Show 6 hidden projects...</summary>

- <b><a href="https://github.com/spray/spray-json">spray-json</a></b> (🥇20 ·  ⭐ 970 · 💀) - A lightweight, clean and simple JSON implementation in Scala. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/typelevel/jawn">jawn</a></b> (🥉17 ·  ⭐ 420 · ➕) - Jawn is for parsing jay-sawn (JSON). <code>❗Unlicensed</code>
- <b><a href="https://github.com/fomkin/pushka">pushka</a></b> (🥉10 ·  ⭐ 74 · 💀) - ABANDONED Pure Scala serialization library with annotations. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/scala-jsonapi/scala-jsonapi">scala-jsonapi</a></b> (🥉9 ·  ⭐ 110 · 💀) - Scala support library for integrating the JSON API.. <code>❗Unlicensed</code>
- <b><a href="https://github.com/battermann/sbt-json">sbt-json</a></b> (🥉7 ·  ⭐ 31 · 💀) - sbt plugin that generates Scala case classes for easy, statically typed.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/nestorpersist/json">json</a></b> (🥉3 ·  ⭐ 11 · 💀) - Persist-Json, a Fast Json Parser Written in Scala. <code>❗Unlicensed</code>
</details>

---

## Related Resources

- [**Best-of lists**](https://best-of.org): Discover other best-of lists with awesome open-source projects on all kinds of topics.

## Contribution

Contributions are encouraged and always welcome! If you like to add or update projects, choose one of the following ways:

- Open an issue by selecting one of the provided categories from the [issue page](https://github.com/stkeky/best-of-scala/issues/new/choose) and fill in the requested information.
- Modify the [projects.yaml](https://github.com/stkeky/best-of-scala/blob/main/projects.yaml) with your additions or changes, and submit a pull request. This can also be done directly via the [Github UI](https://github.com/stkeky/best-of-scala/edit/main/projects.yaml).

If you like to contribute to or share suggestions regarding the project metadata collection or markdown generation, please refer to the [best-of-generator](https://github.com/best-of-lists/best-of-generator) repository. If you like to create your own best-of list, we recommend to follow [this guide](https://github.com/best-of-lists/best-of/blob/main/create-best-of-list.md).

For more information on how to add or update projects, please read the [contribution guidelines](https://github.com/stkeky/best-of-scala/blob/main/CONTRIBUTING.md). By participating in this project, you agree to abide by its [Code of Conduct](https://github.com/stkeky/best-of-scala/blob/main/.github/CODE_OF_CONDUCT.md).

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](https://creativecommons.org/licenses/by-sa/4.0/)
