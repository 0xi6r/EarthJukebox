# 🌍 EarthJukebox

**Making Earth science accessible through sound.**

EarthJukebox is an accessible, multi-sensory platform that transforms NASA Earth science visualizations and scientific data into sound. Our goal is to make the science behind our changing planet accessible to everyone, including people who are visually impaired.

By combining NASA's Earth Information Center (EIC) visualizations with dynamic data sonification, users can explore and experience Earth's changing systems through sound.

---

## About the Challenge

NASA's Earth Information Center (EIC) produces stunning visualizations of our changing planet. These visualizations help people understand complex Earth science phenomena, but presenting scientific information through visuals alone limits accessibility.

The challenge is to make Earth science more accessible, engaging, and multi-sensory by translating sight into sound.

We are tasked with building an **Earth Jukebox**: an interface, script, or application that pairs EIC visual frames with dynamic sonifications generated in real time.

## Understanding the Challenge

NASA's EIC uses scientific data to visualize different aspects of our planet, including:

- **Climate change:** Rising global temperatures and changing climate patterns.
- **Ocean dynamics:** Sea-level changes, ocean temperatures, and melting ice.
- **Deforestation:** Forest cover loss and vegetation changes.
- **Weather patterns:** Atmospheric conditions and environmental changes.
- **Ecosystems:** Changes in vegetation and Earth's natural systems.

The challenge is that these visualizations primarily communicate through sight.

We want to introduce another way of experiencing this information: **sound.**

## Our Solution: EarthJukebox

We envision EarthJukebox as a streaming-style platform for exploring NASA Earth science visualizations through sound.

Think of it as a music streaming experience, but instead of streaming songs, users explore NASA Earth data through synchronized visualizations and generated soundscapes.

### How It Works

1. **NASA Earth Data:** Obtain Earth science visualizations and their underlying scientific data from NASA's Earth Information Center.
2. **Data Sonification:** Process and analyze the scientific data, translating meaningful data characteristics into audio using properties such as pitch, frequency, rhythm, and intensity.
3. **EarthJukebox:** Present the visualizations and their corresponding sonifications through an interactive platform where users can browse, select, and play different Earth science experiences.

### The User Experience

A user visits EarthJukebox, explores available Earth science visualizations, selects a playlist or visualization, and presses play.

The platform presents the corresponding visualization alongside its generated soundscape, allowing users to experience and understand the underlying scientific information through audio.

For visually impaired users, audio becomes an alternative way to explore and interpret Earth science.

## Important Distinction: Image-to-Speech vs. Data Sonification

EarthJukebox is not an image-to-speech application.

- **Image-to-speech:** Describes the contents of an image using spoken language.
- **Data sonification:** Translates underlying scientific data into sound, allowing users to perceive patterns, variations, and changes through audio.

Our focus is data sonification. We want users to hear the science, not simply hear someone describe an image.

## Technical Approach

We plan to build EarthJukebox using a frontend and backend architecture.

### Sonification Pipeline

Our sonification engine will follow this general process:

1. **Data Input:** Receive scientific data associated with an Earth visualization.
2. **Data Processing:** Clean, normalize, and prepare the incoming data.
3. **Data Analysis:** Identify meaningful patterns, variations, and data characteristics.
4. **Sound Mapping:** Map scientific measurements and variations to audio properties such as pitch, frequency, rhythm, and volume.
5. **Audio Generation:** Generate the corresponding sound dynamically.
6. **Playback:** Deliver the generated audio to the frontend for playback alongside the visualization.

### Proposed Repository Structure

```text
EarthJukebox/
│
├── frontend/
│   ├── public/
│   ├── src/
│   ├── components/
│   └── ...
│
├── backend/
│   ├── api/
│   │   └── sonification/
│   ├── services/
│   ├── processing/
│   └── ...
│
├── README.md
└── ...
```

**Frontend:** An interactive, streaming-style interface for browsing NASA Earth visualizations, selecting experiences, and playing synchronized audio.

**Backend:** An API-driven service responsible for receiving scientific data, processing it, performing data analysis, and generating sonification output.

## Technology Stack

- **TypeScript:** Primary development language.
- **Next.js:** Frontend framework and application development.
- **Backend API:** Handles data processing and sonification.
- **Audio Processing:** Responsible for translating scientific data into sound.

Additional libraries and technologies will be selected as development progresses.

## Our Mission

We believe access to scientific knowledge should not be limited by how someone experiences the world.

With EarthJukebox, we want to make the story of our changing planet something everyone can see, hear, explore, and understand.

**Don't just see how Earth is changing. Hear it.** 🌍🎧

---

*Built by VoidVerse for the NASA Space Apps Challenge.*