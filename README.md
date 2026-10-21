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

Most of it is private right now, so here is what it is rather than where it lives.

| | |
| :-- | :-- |
| **Voice assistant** | A desktop assistant in one Python file: microphone in, Google's speech API, spoken answer out through `pyttsx3`. Opens sites, tells the time, exits when told to. |
| **Analytics** | Four end-to-end projects — churn modelling, walk-forward sales forecasting, marketing attribution with an A/B test, and a layered SQL warehouse with data-quality rules. |
| **Full-stack** | Auth-heavy builds: a task manager with JWT refresh and RBAC, a Stripe storefront with signed webhooks, Socket.io chat with presence. |
| **Systems** | A URL shortener with rate limiting and Prometheus-style metrics behind Docker and CI, an offline RAG document Q&A API, a Recharts analytics dashboard. |
| **IoT** | Sensor work on ESP32 and Raspberry Pi boards, and a multi-tenant gym management SaaS with a WhatsApp notification service. |

### In action

A real run of the voice assistant, straight from the source:

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
