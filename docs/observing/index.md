# Observing

`Observing with TRAO` contains the following information
necessary for conducting observations using TRAO:

- How to use TRAO Observation Status (TOS)
- How to use TRAO Observing Tool, "MC"
- How to perform TRAO observations
  - Checking telescope status and observability
  - Pointing and focusing
  - Setting observation frequencies and calibration
  - Checking reference (OFF) position
  - Single pointing PS observation
  - OTF mapping observation
- How to create an observation script, "OT"
- How to write an observation log
- Remote observation
- How to finish observation
- Reporting errors and troubleshooting

## Using TOS

`TOS` (TRAO Observation Status) is a web app accessible through a web browser and
profides the following features:

- Checking real-time TRAO observation status
- Logging previous observation status
- Chatting in real-time among observers
- Messaging for the next observer

The `TOS` window is always open on the observation computers
(both for on-site and remote observation) in the TRAO observation room.

```{note}
On remote observation computers, due to limited screen space,
the `TOS` window may be in the background, 
so you may need to use the application switcher to bring the web browser to the foreground.
```

### How to run TOS

If you cannot find the `TOS` window, you can open `TOS` by following ways:

- ~~Go to [trao.kasi.re.kr/tos](https://trao.kasi.re.kr/tos/) in a web browser~~
**(currently unavailable)**
- Open (double-click) `toswebclient.html` in the `tosweb` folder
on the observation computers' Desktop

### Checking TRAO observation status

`TOS` displays the TRAO observation status in one of the following for states:

- `Maint.` : Telescope maintenance in progress (observation not possible)

```{danger}
When the observation status is `Maint.`,
the observer must never operate telescope using MC.
```

- `Rain` : Weather conditions prevent observation
- `Break` : Idle state
- `On obs.` : Currently on observing

In the `On obs.` state, the observer's location is displayed as one of the following four options:

- `Obs. room` : TRAO observation room (on-site)
- `Away` : Away for a momoent (outside TRAO)
- `Meal` : During a meal (TRAO lounge)
- `Remote` : Remote observing
