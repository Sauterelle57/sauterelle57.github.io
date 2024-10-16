<p align="center">
  <img src="assets/banner_1.jpg" alt="baner">
</p>

## 👋​ Introduction
<p align="justify">
This document is the delivery of the user interface design mini-project in the SOEN 357 course. The aim of this assignment is to follow a structured UX/UI design process to develop a visual prototype of a mobile application, applying the principles studied in class. This process includes several key steps, such as <a href="#-understanding-the-problem">understanding the problem</a>, <a href="#-research--analysis">researching</a> existing solutions, potential user data, <a href="#-fonctionnalities">feature list</a>, creating a <a href="#-persona">persona</a> and <a href="#-empathize-map">empathy map</a>, <a href="#%EF%B8%8F-journey-map">journey map</a>, <a href="#-story-board">storyboarding</a>, <a href="#%EF%B8%8F-sketches">sketching</a>, implementing a <a href="#%EF%B8%8F-user-flow">user flow</a>, creating a <a href="#%EF%B8%8F-wireframes">wireframe</a>, thinking about <a href="#-style">style</a>, then the <a href="#-final-result">final result</a> and a <a href="#-conclusion">conclusion</a>. Each stage of the project will be detailed, highlighting the design choices made, the iterations carried out and the solutions proposed. The final result consists of visual prototypes of the application created with figma.
</p>

<br>

## 🤔 Understanding the Problem
<p align="justify">
The aim of the project is to design a mobile application dedicated to travelers, in particular those traveling alone or to high-risk countries prone to unpredictable events. In these contexts, travelers need frequently updated and verified information, such as travel restrictions, dangers to avoid, local laws and available services. The main objective is to create an intuitive application that not only offers standard travel functions, but also provides quick access to information concerning risk zones, safety rules, health conditions and possible restrictions or conflicts. The application must bring together several services so that users can manage their journeys feeling safe, informed and accompanied, even alone and in unpredictable situations or unfamiliar countries.
</p>
<br>

## 🔍 Research & Analysis

<p align="justify">
Before I started thinking about my app design, I researched existing apps to understand the features and designs used in the travel industry. Among the applications I studied was Opodo, which offers a full range of travel-related services. This analysis enabled me to identify the strengths and limitations of current solutions, and to draw inspiration from them to design an application that meets the specific needs of my users while offering an enhanced experience.
</p>

### Existing App : Opodo
<p align="center">
  <img src="assets/opodo_1.jpg" alt="Opodo_screenshot_1" height="400">
  <img src="assets/opodo_2.jpg" alt="Opodo_screenshot_2" height="400">
  <img src="assets/opodo_3.jpg" alt="Opodo_screenshot_3" height="400">
  <img src="assets/opodo_4.jpg" alt="Opodo_screenshot_4" height="400">
</p>
<br>

<p align="justify">
I soon realized that the fact that I only knew one travel app wasn't going to help me much when it came to creating my super app.
It was more interesting for me to learn from my potential users and ask questions directly to travelers. So I devised a form that was simple and short enough to get as many answers as possible without losing the attention of the people being questioned.
  <br>
I made the form on google form, which seemed to me to be the easiest tool to use and perfectly suited my needs.
I then thought about the best way to get answers from people concerned by my problem. And I finally decided to send the form to a server gathering travelers on the discord social network.
  <br><br>
You can find the results of my survey below.
</p><br>

<h3>
  ❓ Who are the users?
</h3>
<p align="center">
  <img src="assets/form/who.png" alt="who.png" width="500">
  <img src="assets/form/howold.png" alt="howold.png" width="500">
</p>
<p align="justify">
  As can be seen from the results, there is a good diversity of age groups, but the majority of responses come from the 18-25 and 26-35 age groups.
There is a slight gender balance, with a majority of men taking part.
</p><br><br>

<h3>
  ❓ What are their travels?
</h3>
<p align="center">
  <img src="assets/form/timetravel.png" alt="timetravel.png" width="500">
  <img src="assets/form/type.png" alt="type.png" width="500">
</p>
<p align="justify">
  The majority of respondents travel between 1 and 3 times a year.
Pleasure” and ‘Business’ seem to be the most popular types of trip, closely followed by ‘Adventure’.
There is also a good balance between those who prefer to travel solo, with family, or for business reasons.
</p><br><br>

<h3>
  ❓ What is stressful?
</h3>
<p align="center">
  <img src="assets/form/stressful.png" alt="stressful.png" width="600">
</p>
<p align="justify">
  Staying within budget is the most frequently cited aspect, underlining the importance for many travellers of managing their finances while on the move.
Managing visas and documentation is also a major concern, especially for those traveling internationally.
Cultural and linguistic differences also pose significant challenges for respondents, as does the search for interesting local activities.
</p><br><br>

<h3>
  ❓ How are they planning their trips?
</h3>
<p align="center">
  <img src="assets/form/information.png" alt="information.png" width="600">
</p>
<p align="justify">
    Websites are the most common source of information for planning trips, followed by social media and traveler forums.
Family/friends and travel agencies remain reliable sources, although less frequently mentioned.
There's a relatively even split between those who use travel apps and those who don't.
</p><br><br>

<h3>
  ❓ Do they use applications?
</h3>
<p align="center">
  <img src="assets/form/useapp.png" alt="useapp.png" width="600">
</p>
<p align="center">
  <img src="assets/form/whichapp.png" alt="yesapp.png" width="600">
</p>
<p align="justify">
  According to the results, respondents used <strong>Opodo, Airbnb, Booking, Google Flights, Trip.com.</strong> for booking flights and accommodation, 
Google Maps. for route planning and transportation 
for special offers: mainly on platforms such as Airbnb and for flight searches. 
Deepl for interactions in other languages and translations. 
and finally: Instagram for discovering new destinations, and access to special offers.
</p><br><br>


<h3>
  ❓ What is essential for them?
</h3>
<p align="center">
  <img src="assets/form/essentialfeature.png" alt="essentialfeature.png" width="600">
</p>
<p align="justify">
  Among the most important features mentioned by survey participants were: <br>
  - <strong>Flight booking:</strong> Sought-after for air travel planning.<br>
  - <strong>Hotel search:</strong> Useful for accommodation.<br>
  - <strong>Safety alerts:</strong> Essential for keeping abreast of local risks.<br>
  - <strong>Itinerary management:</strong> Helps organize travel and activities during the trip.<br>
  - <strong>Special offers and discounts:</strong> Attract travelers to take advantage of discounted prices.<br>
  - <strong>Destination information:</strong> Information on places to visit, customs and other local information.<br>
  - <strong>Discussions with other travelers:</strong> Encourage the exchange of experiences and advice with other users.
</p><br><br>

<h3>
  ❓ Have they ever encountered a crisis situation?
</h3>
<p align="center">
  <img src="assets/form/crisis.png" alt="crisis.png" width="600">
</p>
<p align="center">
  <img src="assets/form/yescrisis.png" alt="yescrisis.png" width="600">
</p>
<p align="justify">
  One in four people has been faced with a crisis or danger situation in which they were unable to get the help they needed, resulting in a moment of stress that put them at risk. This proportion is considerable, and shows the importance and impact that an application capable of providing them with the information they need quickly and accurately could have.  In particular, users described their wish to know where to find assembly points in the event of a natural disaster (e.g. a volcanic eruption), where to find a doctor, or information on what to do in the event of poisoning or other illnesses. 
local alerts and suggestions for alternative routes or nearby hotels in case of need, local emergency numbers for contacting the police, warnings about the season (e.g. monsoon in Southeast Asia), translation of evacuation plans in case of language barriers, and maps showing safe areas or areas to be avoided.
</p><br>


<h3>
  ❓ What kind of interfaces are they looking for?
</h3>
<p align="center">
  <img src="assets/form/interface1.png" alt="interface1.png" width="500">
</p>
<p align="center">
  <img src="assets/form/interface2.png" alt="interface2.png" width="500">
</p>
<p align="center">
  <img src="assets/form/interface3.png" alt="interface3.png" width="500">
</p>
<p align="justify">
  According to the results, the most important features for an interface according to survey participants are:<br>

- <strong>Simplicity:</strong> A clear, uncluttered, easy-to-understand interface is a priority for most users.<br>
- <strong>Intuitive navigation:</strong> The application should be easy to navigate, with critical information quickly accessible.<br>
- <strong>Visual appeal:</strong> A visually appealing interface is also important, while remaining functional and not overloaded.<br>
- <strong>Accessibility:</strong> Users are looking for an interface with good legibility (e.g. sufficiently large text) and information that is easy to consult without effort.<br>
- <strong>Information first:</strong> The application needs to highlight essential information such as flight or itinerary details, making them easy to find.<br>
- <strong>Ergonomic design:</strong> An ergonomic interface that reduces the need for numerous manipulations and displays notifications discreetly.<br><br>
In short, users want an interface that is simple, visually appealing, intuitive and that highlights important information without cluttering the user up with too many details or unnecessary features.
</p><br><br><br>

<h3>
  ❓ What features do they want to use?
</h3>
<p align="center">
  <img src="assets/form/morefeat1.png" alt="morefeat1.png" width="500">
</p>
<p align="center">
  <img src="assets/form/morefeat2.png" alt="morefeat2.png" width="500">
</p>
<p align="center">
  <img src="assets/form/morefeat3.png" alt="morefeat3.png" width="500">
</p>
<p align="justify">
  Users suggested a variety of complementary services that could enrich a travel app, with a focus on practicality and enhancing the experience. For exemple:<br><br>

- <strong>Practical tools:</strong> currency and local unit converter, real-time weather forecast before and during the trip, as well as a flight price comparator. These tools will help travelers prepare better and save money.<br>
- <strong>Security and assistance:</strong> security alerts, a map of dangerous areas to avoid, quick access to local emergency numbers, and information on visa and passport procedures. These features will ensure greater security and better preparedness in the event of a crisis.<br>
- <strong>Local and social recommendations:</strong> Authentic advice on local activities, restaurants and events, chat with other travelers or locals, and the ability to share or view photos of other users. These services would encourage discovery and social interaction while traveling.<br>
- <strong>Reservation services:</strong> booking cabs on arrival, local guides, and re-booking options in case of flight cancellation. These services would facilitate logistics during the trip.<br>
- <strong>Personalization and adaptation:</strong> The application could adapt to the different stages of the trip, offer personalized recommendations and enable users to save and share their favorite places or tips.<br>
In short, users want practical, personalized services that facilitate logistical aspects (booking, insurance, conversion) while offering reliable local information and safety tools (maps of dangerous areas, alerts). They are also looking for a social and interactive dimension, with ways to connect with other travelers and locals.
</p><br><br>


### App Name
<p align="justify">
The choice of the name <strong>SwayAway</strong> is the fruit of reflection around the core values I wanted to convey through my application: simplicity, serenity and the desire to escape. I was looking for a name that evoked both travel and the feeling of calm, without complexity, that I imagined for the user.
<br>
The word “Sway” came to mind, thinking of the idea of letting yourself be guided naturally, as if swaying slightly, carried by a breeze or a wave. It perfectly captured the fluidity and lightness I wanted to convey. “Away” came next, evoking the sense of escape and discovery of new horizons that many travelers seek. Combining these two terms, SwayAway was born, reflecting the idea of a soothed, obstacle-free journey, where every step is designed to offer a fluid, enjoyable experience.
  <br>
  <br>
The name SwayAway perfectly reflects the spirit of the application: an invitation to let yourself be carried away by the sweetness of travel, while keeping simplicity and serenity at the heart of the experience.
</p>
<br>


## 🙂 Persona
<p align="justify">
  I created the Aiko Sato persona to better understand the needs and expectations of a key user of my app: a solo traveler looking for safety and convenience. By defining her characteristics, fears and frustrations, I was able to focus on features that addressed her concerns, such as the need for reliable, real-time information and personalized guidance. This persona helped me guide the design process, taking into account the real challenges faced by travelers like Aiko.
</p>
<br>
<p align="center">
  <img src="assets/persona.jpg" alt="Persona_2" width="80%">
</p>
<br>

## 🤝 Empathize Map
<p align="justify">
  J'ai élaboré la carte d'empathie pour Aiko Sato afin d'approfondir ma compréhension de ses émotions, motivations et expériences en tant que voyageuse solo. Cet outil visuel me permet de visualiser ce qu'Aiko pense, ressent, dit et fait dans le contexte de ses voyages. En identifiant ses besoins, ses frustrations et ses aspirations, j'ai pu mieux cerner comment mon application pourrait l'accompagner tout au long de son parcours. La carte d'empathie est essentielle pour m'assurer que le design et les fonctionnalités répondent véritablement aux attentes d'utilisateurs comme Aiko, en favorisant une expérience utilisateur positive et adaptée à leurs réalités.
</p>
<br>
<p align="center">
  <img src="assets/empathize_map_2.jpg" alt="Empathize_Map_2">
</p>
<br>

## 🗺️​ Journey Map

<p align="justify">
I created a user map to visualize the user's complete journey through the application, step by step. This tool enabled me to analyze how a user interacts with the various functionalities, from opening the application to achieving their objectives (such as searching for travel information or managing their reservations).
<br>
By building this map, I was able to identify potential friction points and optimize the navigation flow to make the experience as fluid and intuitive as possible. This approach helped me to better understand the user's needs at each stage of their journey, while ensuring that the application remained simple and pleasant to use.
</p>
<br>
<p align="center">
  <img src="assets/journey_map.jpg" alt="Journey_Map">
</p>
<br>

## ✈️​ User Flow
<p align="jusitify">
I was then able to create a user flow to understand the different steps a user would go through when using the application. This user flow illustrates the steps a user follows to find and book a trip through the application. The main objective is to make the process as fluid and intuitive as possible for the user, minimizing the number of steps and providing an optimal user experience.
</p>
<br>
<p align="center">
  <img src="assets/user_flow.jpg" alt="User_Flow" height="1400">
</p>
<br>

## 📖 Story Board
<p align="justify">
I also created a short storyboard featuring Aiko, a young software engineer using the application for the first time. The storyboard illustrates the various stages of her interaction with the application, from opening it to completing her main task, which is to plan her next trip.
<br>
The aim of this storyboard was to show in concrete terms how Aiko, as a typical user, navigates the application, discovers its functionalities and interacts with the interface. </p>
<br>
<p align="center">
  <img src="assets/storyboard.jpg" alt="Story_Board">
</p>
<br>

## ✏️ Sketches
<p align="justify">
To begin my creative process, I decided to produce sketches by hand on paper. This approach enabled me to quickly visualize how my ideas might take shape, and to explore different design possibilities without being restricted by digital tools. These initial sketches provided the basis for my first ideas about the application's structure and navigation.<br>
By sketching out these initial ideas, I was able to concentrate on the essentials: functionality and fluidity of the user experience. These sketches served as a guide throughout the visual development, ensuring that the aesthetic choices made respected the application's initial objective.<br><br>
  However, these sketches are not entirely faithful to the final result, as my ideas evolved throughout the design process. Working on the details and taking into account user feedback, I adjusted certain elements to improve the user experience and make the interface more intuitive and coherent. In this way, the design process enabled me to transform these initial drafts into a more mature version, adapted to users' needs.
</p>

<p align="center">
  <img src="assets/sketches.jpg" alt="sketches.jpg" width="50%">
</p>
<p align="justify">
On the first page you can see 4 different screens, the login page, the map which is the main page, the preview of a destination and finally a more detailed view of the information on a destination with important information on the conditions there and the risks. 
</p><br>

<p align="center">
  <img src="assets/sketches2.jpg" alt="sketches.jpg" width="50%">
</p>
<p align="justify">
The second page shows the special offer screens, the profile page, the saved and completed trips, and the alerts page.</p>
<br><br>

## 🖼️ Wireframes

<p align="justify">
I created wireframes to define the basic structure of my application before getting into the visual details. Wireframes allowed me to focus on the hierarchy of information, the placement of elements and overall navigation without worrying about aesthetic aspects at this stage. They were essential for testing and validating the layout of functionalities, ensuring that the application was intuitive and easy to use.
<br>
By working on the wireframes, I was able to ensure that each screen responded effectively to the user's needs, while maintaining consistency in the navigation flow. This step laid a solid foundation on which to build the final visual design.
</p>
<br>
<p align="center">
  <img src="assets/wireframe_1.png" alt="Wireframe_1" height="400">
  <img src="assets/wireframe_2.png" alt="Wireframe_2" height="400">
  <img src="assets/wireframe_3.png" alt="Wireframe_3" height="400">
  <img src="assets/wireframe_4.png" alt="Wireframe_4" height="400">
  <img src="assets/wireframe_5.png" alt="Wireframe_5" height="400">
  <img src="assets/wireframe_6.png" alt="Wireframe_6" height="400">
  <img src="assets/wireframe_7.png" alt="Wireframe_7" height="400">
</p>

<br>

## 🎨 Style
### Color Palette
<p align="justify">
  For the styling of my app, I drew inspiration from real-life elements that evoke both travel and tranquility. I wanted to capture the serenity one feels lounging on a beach, under the sun, surrounded by palm trees and the gentle sound of the waves. Images of planes soaring into clear skies and a tranquil sea add a dimension of adventure and exploration. By integrating these visual elements, I hope to create an interface that evokes sensations of freedom and relaxation, while facilitating the user experience for those who dream of traveling.
</p>
<br>
<p align="center">
  <img src="assets/search_style.jpg" alt="search_style">
</p>
<br>
<p align="jusitify">
In the process of visually creating my app, I tested several color palettes before finding the combination that I felt best suited the spirit of the app. This research turned out to be a rather straightforward, but above all very inspiring part for me. I explored different shades, seeking to balance contrasting and soothing tones that evoke both adventure and serenity. The final choice of colors reflects the essence of the journey while ensuring a pleasant visual experience for the user.
</p>
<br>
<p align="center">
  <img src="assets/palette.png" alt="Color_palette" width="80%">
</p>
<br>
<br>

### Logo

<p align="justify">
In designing this logo, I thought about the symbolic elements that immediately evoke travel and adventure. I wanted to incorporate visual representations that are universally associated with travel and the discovery of new horizons.
So I decided to combine three key elements: the sun, to symbolize the escape, warmth and light of new experiences; the boat, as a representation of sea travel, evoking exploration and freedom; and finally, the airplane, which embodies modern, fast and global travel.
</p>
<br>
<p align="center">
  <img src="assets/inspiration_logo.png" alt="search_style" width="300">
</p>
<br>
<p align="justify">
The combination of these three elements in the logo reflects the idea of movement, the diversity of means of transport, and the beauty of the landscapes to be discovered on each journey.
After assembling the sun, the boat and the plane to create the logo, I wanted to explore different visual options by declining it in the colors of my palette. This allowed me to test various combinations and see how the colors could reinforce the values and energy I wanted to convey through the design. This declination process was essential in deciding which color theme I wanted to use for my final result.
</p>
<br>
<p align="center">
  <img src="assets/logo/Image58.png" alt="logo" width="75" height="75">
  <img src="assets/logo/Image58.png" alt="logo" width="75" height="75">
  <img src="assets/logo/Image39.png" alt="logo" width="75" height="75">
  <img src="assets/logo/Image40.png" alt="logo" width="75" height="75">
  <img src="assets/logo/Image1.png" alt="logo" width="75" height="75">
  <img src="assets/logo/Image2.png" alt="logo" width="75" height="75">
  <img src="assets/logo/Image45.png" alt="logo" width="75" height="75">
  <img src="assets/logo/Image46.png" alt="logo" width="75" height="75">
  <img src="assets/logo/Image41.png" alt="logo" width="75" height="75">
  <img src="assets/logo/Image42.png" alt="logo" width="75" height="75">
  <img src="assets/logo/Image43.png" alt="logo" width="75" height="75">
  <img src="assets/logo/Image44.png" alt="logo" width="75" height="75"><br>

  <img src="assets/logo/Image8.png" alt="logo" width="75" height="75">
  <img src="assets/logo/Image9.png" alt="logo" width="75" height="75">
  <img src="assets/logo/Image59.png" alt="logo" width="75" height="75">
  <img src="assets/logo/Image59.png" alt="logo" width="75" height="75">
  <img src="assets/logo/Image29.png" alt="logo" width="75" height="75">
  <img src="assets/logo/Image30.png" alt="logo" width="75" height="75">
  <img src="assets/logo/Image23.png" alt="logo" width="75" height="75">
  <img src="assets/logo/Image24.png" alt="logo" width="75" height="75">
  <img src="assets/logo/Image25.png" alt="logo" width="75" height="75">
  <img src="assets/logo/Image26.png" alt="logo" width="75" height="75">
  <img src="assets/logo/Image27.png" alt="logo" width="75" height="75">
  <img src="assets/logo/Image28.png" alt="logo" width="75" height="75"><br>

  <img src="assets/logo/Image3.png" alt="logo" width="75" height="75">
  <img src="assets/logo/Image4.png" alt="logo" width="75" height="75">
  <img src="assets/logo/Image19.png" alt="logo" width="75" height="75">
  <img src="assets/logo/Image20.png" alt="logo" width="75" height="75">
  <img src="assets/logo/Image61.png" alt="logo" width="75" height="75">
  <img src="assets/logo/Image61.png" alt="logo" width="75" height="75">
  <img src="assets/logo/Image21.png" alt="logo" width="75" height="75">
  <img src="assets/logo/Image22.png" alt="logo" width="75" height="75">
  <img src="assets/logo/Image17.png" alt="logo" width="75" height="75">
  <img src="assets/logo/Image18.png" alt="logo" width="75" height="75">
  <img src="assets/logo/Image15.png" alt="logo" width="75" height="75">
  <img src="assets/logo/Image16.png" alt="logo" width="75" height="75"><br>

  <img src="assets/logo/Image6.png" alt="logo" width="75" height="75">
  <img src="assets/logo/Image7.png" alt="logo" width="75" height="75">
  <img src="assets/logo/Image37.png" alt="logo" width="75" height="75">
  <img src="assets/logo/Image38.png" alt="logo" width="75" height="75">
  <img src="assets/logo/Image31.png" alt="logo" width="75" height="75">
  <img src="assets/logo/Image32.png" alt="logo" width="75" height="75">
  <img src="assets/logo/Image56.png" alt="logo" width="75" height="75">
  <img src="assets/logo/Image56.png" alt="logo" width="75" height="75">
  <img src="assets/logo/Image35.png" alt="logo" width="75" height="75">
  <img src="assets/logo/Image36.png" alt="logo" width="75" height="75">
  <img src="assets/logo/Image33.png" alt="logo" width="75" height="75">
  <img src="assets/logo/Image34.png" alt="logo" width="75" height="75"><br>
  
  <img src="assets/logo/Image13.png" alt="logo" width="75" height="75">
  <img src="assets/logo/Image14.png" alt="logo" width="75" height="75">
  <img src="assets/logo/Image64.png" alt="logo" width="75" height="75">
  <img src="assets/logo/Image65.png" alt="logo" width="75" height="75">
  <img src="assets/logo/Image62.png" alt="logo" width="75" height="75">
  <img src="assets/logo/Image63.png" alt="logo" width="75" height="75">
  <img src="assets/logo/Image5.png" alt="logo" width="75" height="75">
  <img src="assets/logo/Image10.png" alt="logo" width="75" height="75">
  <img src="assets/logo/Image57.png" alt="logo" width="75" height="75">
  <img src="assets/logo/Image57.png" alt="logo" width="75" height="75">
  <img src="assets/logo/Image66.png" alt="logo" width="75" height="75">
  <img src="assets/logo/Image67.png" alt="logo" width="75" height="75"><br>

  <img src="assets/logo/Image11.png" alt="logo" width="75" height="75">
  <img src="assets/logo/Image12.png" alt="logo" width="75" height="75">
  <img src="assets/logo/Image49.png" alt="logo" width="75" height="75">
  <img src="assets/logo/Image50.png" alt="logo" width="75" height="75">
  <img src="assets/logo/Image68.png" alt="logo" width="75" height="75">
  <img src="assets/logo/Image69.png" alt="logo" width="75" height="75">
  <img src="assets/logo/Image47.png" alt="logo" width="75" height="75">
  <img src="assets/logo/Image48.png" alt="logo" width="75" height="75">
  <img src="assets/logo/Image51.png" alt="logo" width="75" height="75">
  <img src="assets/logo/Image52.png" alt="logo" width="75" height="75">
  <img src="assets/logo/Image60.png" alt="logo" width="75" height="75">
  <img src="assets/logo/Image60.png" alt="logo" width="75" height="75">
</p>
<br>
<p align="justify">
This process allowed me to test the visual impact of each option. In the end, I chose a version with contrasting, fairly warm colors, always with the idea of reflecting the energy and emotion associated with travel. And above all, the logo that visually appealed to me the most and inspired me the most.
</p>
<br>
<p align="center">
  <img src="assets/logo/Image3.png" alt="logo" widht="300" height="300">
</p>


### Font
<br>
<p align="justify">
To choose the right font for my application, I evaluated several options based on essential criteria such as legibility, aesthetics and consistency with the application's image. My goal was to find a font that was modern, elegant and easy to read on a mobile interface.
</p>
<p align="justify">
  <strong>Afacad Flux<br></strong>
This sans-serif font is both elegant and lightweight, making it attractive for headings and subheadings. However, its thinness can sometimes impair legibility on small screens, especially when text is reduced.
</p>
<p align="left">
  <img src="assets/fonts/Afacad Flux.png" alt="logo" height="200">
</p>
<p align="justify">
  <strong>Aptos<br></strong>
Although this font offers excellent support for non-Latin characters, it's not as suitable for a predominantly Latin-script application. It didn't match the modern visual universe I wanted to create.
</p>
<p align="left">
  <img src="assets/fonts/Aptos.png" alt="logo" height="200">
</p>
<p align="justify">
  <strong>Jost<br></strong>
This font stands out for its balance between modernity and legibility. Its clean, rounded design adds a warm touch while remaining highly legible, even at smaller sizes. It adapts well to the different types of content in the application, whether for titles, subtitles or body text.
</p>
<p align="left">
  <img src="assets/fonts/Jost.png" alt="logo" height="200">
</p>
<p align="justify">
  <strong>Noto Sans Oriya<br></strong>
Although this font was very unique and stylish, it lacked versatility for everyday use in an application. It could have worked in a very specific context, but risked detracting from the user experience due to its complex shape.
</p>
<p align="left">
  <img src="assets/fonts/Noto Sans Oriya.png" alt="logo" height="200">
</p>
<p align="justify">
  <strong>Raleway<br></strong>
Modern and slightly geometric, Aptos has excellent potential for an application interface. Its clarity and balanced character make it ideal for long texts, but it lacked the distinctive look required to reflect the serenity of travel.
</p>
<p align="left">
  <img src="assets/fonts/Raleway.png" alt="logo" height="200">
</p>
<br>

## 🌟 Final Result

<p align="justify">
I was finally able to use the wireframe bases to create the final result on Figma. Starting from the structure and functionalities defined in the wireframes, I was able to refine the visual details and design an interface, integrating examples and more context. This passage from wireframes to the final prototype enabled me to bring the application more life and visualy show how the app would look like. This part took me the longest to do.
</p>
<br>
<p align="center">
  <img src="assets/screens/Connexion screen.png" alt="logo" height="400">
  <img src="assets/screens/Map screen.png" alt="logo" height="400">
  <img src="assets/screens/Card screen.png" alt="logo" height="400">
  <img src="assets/screens/Card up screen.png" alt="logo" height="400">
  <img src="assets/screens/Card up info screen.png" alt="logo" height="400">
  <img src="assets/screens/Offer screen.png" alt="logo" height="400">
  <img src="assets/screens/Profil screen.png" alt="logo" height="400">
  <img src="assets/screens/Alert screen.png" alt="logo" height="400">
  <img src="assets/screens/MyTravel screen.png" alt="logo" height="400">
</p>
<br>
<p align="jusitify">
Once I was satisfied with the result, I had some fun making a quick animated version to better visualize what it might look like on a phone.
</p>
<br>
<p align="center">
  <img src="assets/gif.gif" alt="Demo de l'application" height="400">
</p>
<br>
<br>

## ❔ Conclusion

<p align="justify">
In conclusion, this project enabled me to explore every key stage of the UX/UI design process, from initial research to the creation of final prototypes. I followed a structured methodology that helped me understand the needs of target users, through the creation of personas, empathy maps, sketches and wireframes. Drawing on real-life references and visual inspirations evocative of travel and serenity, I was able to design an application that combines functionality and aesthetics. Every design decision was guided by the desire to offer travelers a fluid, intuitive and secure experience.
The final prototypes reflect these priorities, while incorporating user feedback and best practices in interactive design. Finally, the project was carried out on Figma, and is the result of numerous iterations aimed at offering a solution adapted to travelers in search of safety and simplicity.
</p>
<br>

## 😘 Author

<img src="assets/pp_v2.png" alt="Marie Giacomel" height="150" style="border-radius: 50%; margin-right: 15px;"><br>
<strong>Marie Giacomel</strong><br>
Concordia University, Montreal<br><br>
<p>
  <strong>Student ID:</strong> 40321702<br>
  <strong>Course:</strong> SOEN 357 - User Interface Design<br>
  <strong>Concordia Email:</strong> <a href="mailto:ma_giaco@live.concordia.ca">ma_giaco@live.concordia.ca</a><br>
  <strong>Epitech Email:</strong> <a href="mailto:marie.giacomel@epitech.eu">marie.giacomel@epitech.eu</a><br>
  <strong>GitHub:</strong> <a href="https://github.com/Sauterelle57">Sauterelle57</a><br>
  <strong>LinkedIn:</strong> <a href="https://www.linkedin.com/in/marie-giacomel-331256232/">Marie Giacomel</a>
  <br><br>
</p>

This project is part of my course work at Concordia University as part of my fourth-year exchange program at Epitech.
