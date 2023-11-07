# Using TOS

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

```{seealso}
[Download PDF version of TOS User Manual](TOS_manual.pdf)  
This is the user manual for the previous version of `TOS` app. 
The current version of `TOS` can be run directly in the browser without installation.
```

## How to run TOS

If you cannot find the `TOS` window, you can open `TOS` by following ways:

- ~~Go to [trao.kasi.re.kr/tos](https://trao.kasi.re.kr/tos/) in a web browser~~
**(currently unavailable)**
- Open (double-click) `toswebclient.html` in the `tosweb` folder
on the observation computers' Desktop

## Checking TRAO observation status

You can check the TRAO observation status in `TOS`:

- `Maint.` : Telescope maintenance in progress (observation not possible)
- `Rain` : Weather conditions prevent observation
- `Break` : Idle state
- `On obs.` : Currently on observing

In the `On obs.` state, the observer's location is displayed:

- `Obs. room` : TRAO observation room (on-site)
- `Away` : Away for a momoent (outside TRAO)
- `Meal` : During a meal (TRAO lounge)
- `Remote` : Remote observing

```{danger}
When the observation status is `Maint.`,
the observer must not operate telescope using MC.
```

