---
layout: ecumene
title: The Ecumene
subtitle: A worldbuilding exercise intended to serve as a low-fantasy TTRPG setting.
---

<link rel="stylesheet" href="/assets/css/world-doodles.css">
<script>
$(document).ready(function() {
	$.each($('em.ae'),function(k,v) {
		var em = $(v);
		var date = v.html();
		em.attr('title', date + ' ab egressūs (since The Landing), ' + (7130 - date) + ' years before present');
		em.html(date + 'ae');
	});
});
</script>

## Introduction

Inspired by [Dungeon23](https://seanmccoy.substack.com/p/dungeon23) and its spinoffs (e.g. [Hex23](https://www.youtube.com/watch?v=eDZcY_PYvrk), [World23](https://www.reddit.com/r/worldbuilding/comments/zx7jtp/world23_a_daily_worldbuilding_challenge_for_2023/), etc), the Ecumene is my attempt at creating a campaign setting that may be used in the future in a TTRPG. It isn't intended to comport to any particular regular development schedule, but rather to explore the different fields of worldbuilding in a freeform manner, developing from first principles and developing depth in each field over time.

Key concepts behind designing The Ecumene:
- doppelganger worlds with divergent fates
- duality of light and dark (and interrogating the assumption that it maps to good and evil)
- low fantasy, with casting ability confined to certain ancestries and heritages
- relics of advanced technology from an ancient non-human civilization

## Cosmology

### Ador & Ayn: Twin Suns

The Ecumene is located within a binary star system, in which both stars have their own inhabited planets. The Ecumene is the sole inhabited world orbiting Ador (though its twin had once been inhabitable)

<ul class="tree">
	<li><a style="font-weight:bold">Ador-Ayn System</a>
		<ul>
			<li>
				<a>Ador</a>
				<aside id="infobox-ador">
					<h4>Ador</h4>
					<div class="doodle">
						<div class="surface"></div>
						<div class="companion"></div>
					</div>
					<p>G9V Yellow-Orange Main Sequence Dwarf Star</p>
				</aside>
				<ul>
					<li>
						<a>Iubar</a>
						<aside id="infobox-iubar">
							<h4>Iubar</h4>
							<div class="doodle">
								<div class="surface"></div>
							</div>
							<p>Terrestrial, Uninhabitable (0.29M🜨)</p>
							<p>Pearlescent Clouds over dark-grey basalt surface</p>
						</aside>
					</li>
					<li>
						<a>The Ecumene</a>
						<aside id="infobox-ecumene">
							<h4>The Ecumene</h4>
							<div class="doodle">
								<div class="surface"></div>
								<div class="moon"></div>
							</div>
							<p>Terrestrial, Habitable (0.472M🜨)</p>
							<p>Wispy White Clouds over Water Surface with Brown-to-Green Land</p>
						</aside>
						<span>&</span>
						<a>Maranthisa</a>
						<aside id="infobox-maranthisa">
							<h4>Maranthisa</h4>
							<div class="doodle">
								<div class="surface"></div>
								<div class="moon"></div>
							</div>
							<p>Terrestrial, No Longer Habitable (0.099M🜨)</p>
							<p>Khaki-Grey Land with Brown Seas pocked with white-rayed craters</p>
						</aside>
						<ul>
							<li>
								<a>Elder Sister</a>
								<aside>
									<h4>Elder Sister</h4>
									<p>Spheroidal Planetoid</p>
									<p>Beige</p>
								</aside>
							</li>
							<li>
								<a>Middle Sister</a>
								<aside>
									<h4>Middle Sister</h4>
									<p>Semi-Spheroidal Planetoid</p>
									<p>Ash Grey</p>
								</aside>
							</li>
							<li>
								<a>Younger Sister</a>
								<aside>
									<h4>Younger Sister</h4>
									<p>Irregularly-Spheroidal Planetoid</p>
									<p>Copper Grey</p>
								</aside>
							</li>
						</ul>
					</li>
					<li>
						<a>Mellete</a>
						<aside>
							<h4>Mellete</h4>
							<p>Terrestrial, Uninhabitable (0.2M🜨)</p>
							<p>Minimal atmosphere over an old Light-Grey Silicate Surface</p>
						</aside>
					</li>
				</ul>
			</li>
			<li>
				<a>Ayn</a>
				<aside id="infobox-ayn">
					<h4>Ayn</h4>
					<div class="doodle">
						<div class="surface"></div>
						<div class="companion"></div>
					</div>
					<p>M0V Orange-Red Main Sequence Dwarf Star</p>
				</aside>
				<ul>
					<li>
						<a>Ninurta</a>
						<aside>
							<h4>Ninurta</h4>
							<p>Terrestrial, Marginally Habitable, Tide-Locked to Ayn (1.2M🜨)</p>
							<p>Eyeball World: Sand (Day), Seas & Lush Land (Twilight), Ice (Night)</p>
						</aside>
					</li>
					<li>
						<a>Marduk</a>
						<aside id="infobox-marduk">
							<h4>Marduk</h4>
							<div class="doodle">
								<div class="surface"></div>
								<div class="moon"></div>
							</div>
							<p>Gas Giant (~15M🜨)</p>
							<p>Banded Blue and White (Class II: Water Clouds)</p>
						</aside>
						<ul>
							<li>
								<a>Nabu</a>
								<aside>
									<h4>Nabu</h4>
									<p>Terrestrial, Habitable Moon, Tide-Locked to Marduk (0.6M🜨)</p>
									<p>High volcanism, thick atmosphere keeps it warm</p>
								</aside>
							</li>
						</ul>
					</li>
					<li>
						<a>Asteroid Belt</a>
					</li>
					<li>
						<a>Nergal</a>
						<aside>
							<h4>Nergal</h4>
							<p>Gas Dwarf (4-5M🜨)</p>
							<p>Banded Yellows (Class I: Ammonia Clouds)</p>
						</aside>
					</li>
				</ul>
			</li>
		</ul>
	</li>
</ul>

Ador and Ayn have an orbital period of 96.26 Ecumene years and a moderately eccentric orbit. During close approaches, the planets of each star undergo a period of warming, distorting prevailing weather patterns.

### Ecumene & Maranthisa: Twin Worlds

The Ecumene and the Maranthisa form a double planet system (the Maranthisa is 2/3 the radius and 2/5 the mass of the Ecumene), with three moons orbiting their barycenter. The Ecumene and the Maranthisa are mutually tidally locked, resulting in an unusually long rotational period of 65.784 hours. The Ecumene is currently habitable; the Maranthisa used to be habitable, but a cataclysm rendered it uninhabitable over four thousand three hundred years ago.

Due to being mutually tidally locked, each world has a "light side" and a "dark side", that is, a side which faces the other world and a side which faces away. Because of their relative size and relatively high albedo, night on the light side is more akin a perpetual twilight. The two worlds are close enough that large geographic features are visible with the naked eye.

### The Three Sisters

The Three Sisters are the moons of Ecumene-Maranthisa. The three are locked in orbital resonance with one another and with Ecumene-Maranthisa.

## Geography of the Ecumene

The Ecumene is a wet, inhabitable world similar to Earth. To contrast with Earth, the Ecumene is smaller (0.766 Earth Radii, 0.471 Earth Masses), has more of its surface covered with water (22/25 vs 18/25), and significantly less arid and semi-arid land.

Six major continents, four minor continents, and countless islands. Most of the Ecumene's dry land is located in the southern hemisphere, with the northern hemisphere dominated by a massive ocean.

## Peoples & Politics

### Thinking Kinds

The Ecumene is home to several sapient species, referred to as the Thinking Kinds. By far the most populous of these is Mankind, which is indigenous to the Ecumene and has a dominant role in its histories and societies. A significantly less populous but historically critical kind is Elfkind, whose first arrival to the Ecumene marks the beginning of the most common calendar era, (a.e. *ab Egressu* "since the Landing") and who evacuated to the Ecumene following the Cataclysm of *2791*{: .ae}, when their homeworld became uninhabitable.

Other notable kinds are:
* Halflingkind, who are an offshoot of Mankind and are known for their short stature, pinkish skin, and talent for stealth.
* Goblinkind, who claim to be indigenous to the Ecumene and are known for their invasiveness, disgusting habits, and talent for trouble.
* Koboldkind, who originate from Ninurta, and are known for their cautiousness, devoted, and resilient.

### Major Polities

One of the most important polities within human history is that of the Imperium, a state which, at its high point, dominated two continents and whose cultural influence reached five continents. In the current year of 7130 a.e., the Imperium itself is significantly smaller but continues to be a center of cultural, political, and economic influence; areas touched by its influence and/or rule over the centuries continue to be governed in a manner emulating the Imperium.

## Culture

Eu tincidunt tortor aliquam nulla facilisi. At imperdiet dui accumsan sit amet nulla facilisi morbi tempus. Purus viverra accumsan in nisl nisi scelerisque eu ultrices vitae. Morbi leo urna molestie at elementum eu. Dignissim diam quis enim lobortis scelerisque fermentum. Morbi quis commodo odio aenean sed. Morbi non arcu risus quis. Nibh mauris cursus mattis molestie a. Pellentesque massa placerat duis ultricies lacus sed turpis tincidunt id. Ut placerat orci nulla pellentesque dignissim.

## Technology

Hac habitasse platea dictumst quisque sagittis purus sit amet. Sem viverra aliquet eget sit amet tellus cras adipiscing enim. Vitae purus faucibus ornare suspendisse sed nisi. Facilisis sed odio morbi quis commodo odio aenean sed. Sed risus ultricies tristique nulla aliquet enim. Facilisis sed odio morbi quis. Cras tincidunt lobortis feugiat vivamus at. Eget egestas purus viverra accumsan in nisl nisi scelerisque. Ut faucibus pulvinar elementum integer enim neque volutpat. Scelerisque eleifend donec pretium vulputate sapien. Dui sapien eget mi proin sed libero enim sed faucibus. Blandit cursus risus at ultrices. Malesuada pellentesque elit eget gravida cum sociis natoque penatibus et. Sed sed risus pretium quam vulputate dignissim suspendisse. Quis ipsum suspendisse ultrices gravida dictum fusce ut.
