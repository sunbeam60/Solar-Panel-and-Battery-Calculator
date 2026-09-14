# Solar Panel and Battery Calculator

[Start the Calculator](https://sunbeam60.github.io/Solar-Panel-and-Battery-Calculator/)

<img width="539" height="627" alt="image" src="https://github.com/user-attachments/assets/c608782e-10ab-4529-bea2-20227f5a86cf" />

- Wondering how much energy your new solar panels will generate?
- Trying to figure out how big a battery you need?
- How will that all fit in with your home energy use?
- And what about if you changed to a different energy tariff that paid differently?
- Deploying a solar powered device in a remote location and wondering if it's strong enough to last through the winter?
- Thinking about adding a bit of balcony solar and plug-in battery?
- Wondering how you will convince your partner that this is a good thing to spend your money on (the origin of this vibe-coded project)?

The answers to all those questions are (probably) in this calculator.

## How to use the calculator
[Start the Calculator](https://sunbeam60.github.io/Solar-Panel-and-Battery-Calculator/)

### Solar panels
<img width="200" alt="image" src="https://github.com/user-attachments/assets/f9d6e434-2036-4cc2-8e35-02d1b6f30955" />

Pick the location, the angle and orientation of the solar panel.

Using NASA sky clarity data and simulated sun position, the expected, unshaded output of the panels are shown. You can play with different orientations and angles to see the effect on the output.

The "Advanced" section holds the performance ratio, sky clearness, ground albedo and "Output fade" — how much output the panels lose each year (0.5 % is NREL's field median); it weakens the panels year by year in the lifetime savings, payback and return.

If you're only considering adding a battery to take advantage of cheap overnight or midday energy, click "No solar"

### Battery
<img width="200" alt="image" src="https://github.com/user-attachments/assets/7ed2f369-11e7-4333-9685-d53a13a3f496" />

Add some battery storage; there are a few presets for commonplace battery models, but if you can't find the one you're looking for, you can manually set battery size, limits, depth, efficiency in the "Advanced" section. "Capacity fade" there is how much usable capacity the battery loses each year (2 % is a typical figure for home LiFePO₄); it shrinks the battery year by year in the lifetime savings, payback and return. Two charts show how the battery behaves: the state of charge through a day — the best day, an average day and the worst day of the year — and the highest and lowest charge it reaches on every day of the year.

### Usage
<img width="200" alt="image" src="https://github.com/user-attachments/assets/dbef74c7-ae7c-4e96-8856-986d64c3f687" />

Add your energy usage. For homes, it's easiest to pick the "Household" preset and the scale the usage to your annual usage by manually set the "Annual use" value; the hourly use settings are scaled combined.

If your usage is atypical, you you manually click and drag to set hour by hour figures. It's far easier to draw the general usage shape and then scale that shape by use the "Annual use" field.

### Cost & Return
<img width="200" alt="image" src="https://github.com/user-attachments/assets/f2161f25-570b-4298-aa98-c824876c4eec" />

Set your electricity rate; in many situations, once you add solar to your building, you'll start moving towards a flexible rate that allows you to sell solar energy back to the grid. 

The presets hold common (UK) flexible tariffs, but you can click and drag to set your own or simply clock "Flatten" for static pricing (scale by using the Average field).

Many flexible tariffs pay you for exporting energy back to the grid. In some cases, this is a flat rate, in others a flexible rate. Like the cost, export pricing can be drawn manually if one of the supplied presets don't suit you.

Turn on "Grid charging" under "Advanced" to buy cheap electricity for the battery. A dashed line appears across the import prices at the threshold, the hours at or below it turn blue, and the handle on the right of the line drags the threshold up and down.

"Export limit" under "Advanced" caps how fast surplus can leave the property; anything above it is thrown away. The default is 3.68 kW, the most a single-phase UK connection may export under G98 without DNO approval. Set it to 0 for no limit.

For deployable solar nodes, where you are simply modelling how the solar node will operate during the dark winter months) the Cost & Return section can simply be ignored.

## Need to share your calculation with someone else?
<img width="45" height="44" alt="image" src="https://github.com/user-attachments/assets/10dc5f93-d7b4-40be-b953-82f4d386996b" />

Click the share link in the top right of the page.

## Notes
- Started as a vibe coded project to model behaviour of some MeshCore nodes over winter.
- Evolved into a home calculator on request.
- Evolved further based on user requests.
- Might not be useful to you.
