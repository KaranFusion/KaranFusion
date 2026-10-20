```text
██╗  ██╗ █████╗ ██████╗  █████╗ ███╗   ██╗
██║ ██╔╝██╔══██╗██╔══██╗██╔══██╗████╗  ██║
█████╔╝ ███████║██████╔╝███████║██╔██╗ ██║
██╔═██╗ ██╔══██║██╔══██╗██╔══██║██║╚██╗██║
██║  ██╗██║  ██║██║  ██║██║  ██║██║ ╚████║
╚═╝  ╚═╝╚═╝  ╚═╝╚═╝  ╚═╝╚═╝  ╚═╝╚═╝  ╚═══╝
```

<div align="center">

**IoT developer — I make small computers talk to the physical world.**

[LinkedIn](https://www.linkedin.com/in/karan-samrit-380918309/) &nbsp;·&nbsp; [Email](mailto:karansamrit26@gmail.com) &nbsp;·&nbsp; [Repositories](https://github.com/KaranFusion?tab=repositories)

</div>

---

### About

I build small machines that notice things. A sensor on a board, a script that listens to it,
and enough glue in between to turn a reading into a decision. Most of my projects start on a
breadboard and end up as something that actually gets used around the house.

On the microcontroller side it's C++ and the Arduino toolchain. On the machine sitting next to
it, Python. Right now I'm trying to get small models to run on the board itself instead of
calling out to the cloud — a sensor that needs Wi-Fi to think is a sensor that stops thinking
when the Wi-Fi does.

I care about the boring parts: the sensor that only fails when nobody is watching, the serial
port that works for a week and then doesn't, the thing that has to keep running unattended.

### Right now

- **Building** — voice and sensor automation on the ESP32.
- **Learning** — fitting ML models into a few hundred kilobytes of RAM.
- **Open to** — collaboration on open-source IoT and robotics projects.

### Toolbox

| Layer | What I use |
| :-- | :-- |
| Languages | Python · C++ · SQL |
| Boards & firmware | Arduino · ESP32 / ESP8266 · Raspberry Pi |
| Voice | `speech_recognition` · `pyttsx3` |
| Data | MySQL |
| Around the edges | Arduino IDE · Git · MySQL Workbench |

### How a project comes together

```text
  sensors         board         software        output   
┌──────────┐   ┌──────────┐   ┌──────────┐   ┌──────────┐
│  DHT22   │──▶│  ESP32   │──▶│  Python  │──▶│   MQTT   │
│ PIR, LDR │   │ RPi 4/5  │   │glue code │   │dashboard │
└──────────┘   └──────────┘   └──────────┘   └──────────┘
```

### Selected work

| Project | What it is |
| :-- | :-- |
| [**jarvis-voice-assistant**](https://github.com/KaranFusion/jarvis-voice-assistant) | A desktop voice assistant in a single Python file. Listens through Google's speech API, answers with `pyttsx3`, opens sites, checks the time, exits when you tell it to. |
| [**Library-Management-System-**](https://github.com/KaranFusion/Library-Management-System-) | A MySQL schema for books, members and lending, plus the joins, aggregates and constraints that keep it honest — including the query that finds books nobody has brought back. |

### In action

A real run of the assistant, straight from the source:

```console
$ python jarvis.karan.py
Good Morning, Karan!
I am Jarvis. How can I help you?
Listening...
Recognizing...
You said: what time is it
The time is 09:41:22
Listening...
Recognizing...
You said: open youtube
Opening YouTube
Listening...
Recognizing...
You said: exit
Goodbye, Karan!
```

### Contact

The fastest way to reach me is [LinkedIn](https://www.linkedin.com/in/karan-samrit-380918309/),
or by [email](mailto:karansamrit26@gmail.com). Happy to talk about IoT, embedded work,
robotics, or anything that needs a sensor and a bit of stubbornness.

<sub>Built with plain Markdown, a text editor and figlet. No templates, no generated stats.</sub>
