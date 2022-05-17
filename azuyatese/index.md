---
layout: light
title: Äzüyätese
---

# Äzüyätese
{:.no_toc}

* TOC
{:toc}

## Introduction

{% include figure.html url="/assets/img/flag.svg" description="Flag of the Azuyat State" %}
Chancery Speech is the standard language variety used by the governing authority in Äzüyät, an island country that dominates the Bend of the Archipelago. This country had long been divided into a complex network of chiefdoms, which allowed for the development of a diverse family of dialects.

Äzüyätese dialects have been grouped into four zones:
- Central
	- Central North
	- Central West
	- Central East
- Southern
	- Near Southern
	- Far Southern

Upon the establishment of a unified government, a standardized variety was developed from within the Central West dialect zone: Chancery. Early records that document contact between Azuyat and Uuiihinellun (*The Land of Great Princes*) are in a now extinct Southern variety, which has contributed significant vocabulary to the inter-regional Trade speech. This Trade Speech is otherwise categorized as a Central East dialect.

## Phonology

### Consonants

|            | Labial   | Dental  | Lateral | Retroflex | Palatal | Velar | Uvular |
|------------|----------|---------|---------|-----------|---------|-------|--------|
| Nasal      | /m/      | /n/     |         |           |         | /ŋ/   |        |
| Plosive    | /p/      | /t/     |         | /ṭ/       |         | /k/   | /q/    |
| Sibilant   |          | /s/     |         |           |         |       |        |
| Continuant | /ʋ/      |         | /l/     | /r/       | /j/     |       | /ʀ/    |
{:.phonology}

### Vowels

|      | Neutral  |   | Front    |   | Back     |
|------|----------|---|----------|---|----------|
| High | /i/ /ii/ |   | /ü/ /üü/ |   | /u/ /uu/ |
| Mid  | /e/ /ee/ |   | /ö/ /öö/ |   | /o/ /oo/ |
| Low  |          |   | /ä/ /ää/ |   | /a/ /aa/ |
{:.phonology}

### Phonotactics

All dialect zones of Azuyatese exhibit strong regressive assimilation pressure, which seeks to unify the manner of articulation in a consonant cluster.

In all zones:
: Plosive + Continuant (**tv**) &rarr; Continuant + Continuant (**lv**)
: Plosive + Nasal (**pn**) &rarr; Nasal + Nasal (**mn**)

In all Central and the Near Southern zones:
: Continuant + Plosive (**lk**) &rarr; Plosive + Plosive (**tk**)

In the Central East and all Southern zones:
: Nasal + Plosive (**nt**) &rarr; Geminate Plosive (**tt**)
: Continuant + Sibilant (**vs**) &rarr; Plosive + Sibilant (**ps**)

In all Southern zones:
: Nasal + Nasal (**mn**) &rarr; Geminate Nasal (**nn**)

## Morphology

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec sagittis lobortis sapien, in fringilla urna blandit ac. Fusce semper augue sit amet erat venenatis interdum. Donec laoreet eget diam quis vestibulum. Morbi enim lacus, accumsan id iaculis in, lobortis quis elit. Vivamus placerat est tortor, id mollis ligula pellentesque eget. Donec at mauris ultrices, rutrum orci eu, suscipit dui. Etiam lobortis in mi sed venenatis.

### Nominals

Aenean accumsan ornare blandit. Interdum et malesuada fames ac ante ipsum primis in faucibus. Nulla non erat sit amet nisi pellentesque vulputate. In eleifend accumsan nisl sed ultrices. Fusce id lectus vitae sem semper varius. Phasellus tellus turpis, tempus et viverra rhoncus, mollis et libero. Donec et lorem nunc. Etiam gravida, velit sit amet ultricies ullamcorper, neque lorem dictum ipsum, sed tincidunt lacus enim ac purus. 

### Verbs

Maecenas hendrerit mi quam, ac interdum nibh lobortis vel. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. Mauris sit amet orci a justo malesuada tempor. Nulla dictum placerat ante sit amet cursus. Sed eu urna blandit, bibendum arcu et, venenatis quam. Cras quis quam mollis, pharetra elit a, iaculis nisl. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia curae; Cras dapibus ac risus id condimentum. Morbi euismod viverra ligula, non ultricies tellus dignissim vel. Sed hendrerit ante non fringilla dapibus. Maecenas faucibus convallis ante et elementum. 

## Lexicon

<table class="sortable">
	{% for row in site.data.lexicon %}
		{% if forloop.first %}
		<thead>
			<tr>
				{% for pair in row %}
				<th>{{ pair[0] }}</th>
				{% endfor %}
			</tr>
		</thead>
		{% endif %}
		
		{% tablerow pair in row %}
			{{ pair[1] }}
		{% endtablerow %}
	{% endfor %}
</table>

<script>
	$('.sortable').tablesort();
</script>