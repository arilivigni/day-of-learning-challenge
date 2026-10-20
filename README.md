# The Day of Learning Challenge

**GitHub Day of Learning | 2-hour workshop game challenge | Canvas Extension Edition**

Build **Mona's Octoverse Arcade**: a browser game starring Mona the Octocat as
the hero and Copilot as the sidekick. Ship it as a **Copilot App canvas
extension** that installs and opens inside the Copilot App. Every team starts
from the same prompt, then makes the game its own.

This public template is your team's starting repository and challenge guide.
It contains **only this README**, not a playable game or canvas extension.
Your facilitator will provide the known-good canvas starter separately.

Read the [attendee website](https://ghlearn.github.io/monas-octoverse-arcade/)
for the same challenge in website form.

**Create your team's repository**

1. Have one teammate open
   [this template repository](https://github.com/ghlearn/day-of-learning-challenge)
   and select **Use this template > Create a new repository**.
2. Choose the owning account or organization and a repository name for your
   team. Make sure the judges can access it.
3. Invite your teammates as collaborators and share the new repository URL.
   Everyone should work in this one shared repository, rather than creating
   separate copies.
4. Clone your team's repository and open it in the Copilot App. Obtain the
   canvas starter from your facilitator, add its extension folder to your
   repository, and confirm it installs and opens before building.
5. Commit and push your team's extension changes so the submitted repository
   contains the version shown in your demo.

**Challenge topics:** [Prompt](#prompt) | [Teams](#teams) |
[Canvas extension](#canvas-extension) | [Agenda](#agenda) |
[Submit](#submit) | [Judging](#judging) | [Awards](#awards) |
[Principles](#principles)

## Prompt

Every team starts with this prompt in the Copilot App. It sets the baseline,
not the limit.

> Build a Copilot App canvas extension called Mona's Octoverse Arcade. Start
> from the provided canvas starter template. Inside the canvas, create a game
> where Mona the Octocat collects green commit-squares while dodging red bugs.
> Track the score, increase speed over time, and show a game-over screen with
> a restart button. Copilot appears as a sidekick that gives an encouraging
> tip every 10 points. The extension must install cleanly and open as a
> playable canvas. Keep it to HTML/CSS/vanilla JS inside the canvas - no
> external build step.

**The baseline**

- Mona collects green commit squares and dodges red bugs.
- The score is tracked, and the speed increases over time.
- A game-over screen has a restart button.
- Copilot cheers you on with a tip every 10 points.

**Make it yours**

- **Rethink the world:** levels, settings, and a story that make Mona's arcade
  feel like yours.
- **Invent power-ups:** shields, magnets, merge combos, or boss bugs.
- **Give Copilot personality:** make the sidekick funny, helpful, or full of
  surprises.
- **Find your style:** art direction, animation, and sound that make people
  want to keep playing.

## Teams

Up to 150 people may take part, so everyone builds in a team.

- **4-6 people per team:** minimum 4, maximum 6. Aim for 5.
- **Choose a team name** during kickoff. Use it on your submission.
- **One shared repository:** keep your team's extension in one repository
  that judges can open.

With 150 participants, teams of 5 make about 30 teams (25-38, depending on
team size). If your group has fewer than 4 people, join another group. If it
has more than 6, split into two teams.

## Canvas extension

Your game cannot be a loose HTML file. It must be a **Copilot App canvas
extension** that:

1. **Lives in its own folder**, with an `extension.mjs` that registers a
   canvas (the game UI).
2. **Can be installed** into the Copilot App via `install_extension` from a
   GitHub gist or repository folder, or by placing the folder in the
   extensions directory.
3. **Runs as a canvas** when the agent opens it with `open_canvas`. The game
   renders in the side panel and is playable.

Start from the **known-good canvas starter provided by your facilitator**.
This README-only repository is not that starter and does not include an
`extension.mjs`. Add the starter's extension folder to your team's repository
and keep the extension files together as you build.

Use HTML, CSS, and vanilla JavaScript inside the canvas, with **no external
build step**. You will learn the real extension model: manifest, canvas
registration, install, and launch, not just front-end code.

## Agenda

The workshop lasts **2 hours**.

| Time | Phase | What to do |
| --- | --- | --- |
| 0:00-0:15 | Kickoff & teams | See the target canvas extension, get the starter prompt and rubric, form teams of 4-6, and choose a team name. |
| 0:15-0:25 | Install the starter | Install and open the facilitator-provided starter canvas template. Confirm it runs. |
| 0:25-1:15 | Build your game | Start from the prompt, then build your team's version inside the canvas with the Copilot App. |
| 1:15-1:35 | Power-up | Pick a stretch goal: leaderboard, sound, animation, theming, or your own idea. |
| 1:35-2:00 | Record & submit | Record a demo video of up to 90 seconds and post your submission in the challenge Discussion before the workshop ends. |

## Submit

Before the workshop ends at **2:00**, one teammate posts your team's
submission as a **single comment in the challenge Discussion**. Your
facilitator will share the Discussion link; do not submit in a separate
Discussion in your team's repository.

Include all four items:

1. **Team name:** the name your team chose at kickoff.
2. **Description:** a few sentences about your game, your creative spin, and
   your power-up.
3. **Demo video:** up to **90 seconds**. Show the extension installing,
   opening as a canvas, and being played. Attach the video to your comment
   or add a link that judges can access.
4. **Repository link:** your team's repository containing the extension
   folder. Make sure judges can access it and that your changes are pushed.

You can copy this into your submission comment and replace the placeholders:

```markdown
**Team name:** <your team name>

**Description:** <your game, creative spin, and power-up>

**Demo video:** <attach a video or paste an accessible link; up to 90 seconds>

**Repository:** <URL of your team's repository containing the extension folder>
```

## Judging

After the workshop, judges review every submission's demo video and
repository against this **25-point rubric**. They choose all three award
winners and announce them in the challenge Discussion. **There is no
audience vote.**

| Criteria | Points | What judges look for |
| --- | ---: | --- |
| **It works:** installs & runs as a canvas | 8 | Extension installs, canvas opens, game is actually playable. |
| **Fun factor** | 6 | Is it enjoyable? Would you play again? |
| **GitHub theme** | 5 | Creative use of Mona & Copilot as characters. |
| **Polish** | 3 | Visuals, animations, sound, game-over/restart flow. |
| **Wow / stretch** | 3 | A power-up feature that surprised the judges. |
| **Total** | **25** | |

## Awards

The **judges decide** all three categories. Each category winner takes home
**swag**.

| Award | Recognizes |
| --- | --- |
| **Overall Winner** | Best total rubric score across all criteria. |
| **Best Design** | The best-looking, most visually striking game (Polish). |
| **Most Fun** | The game the judges most wanted to keep playing (Fun factor). |

**Award rollover rule:** a team can win more than one category. However, if
the Overall Winner also tops another category, that second award rolls to
the runner-up to spread the recognition.

## Principles

- **Rubric up front:** teams know what is judged before building.
- **Known-good starter:** a working canvas starter makes "install & run"
  achievable for everyone.
- **Reward working software:** "it works" has the highest weight, with 8 of
  25 points for installing and running as a canvas.
- **Shared theme, personal spin:** every team starts from the same prompt
  and builds Mona's Arcade, then makes it its own.

---

> **Note:** This is an independent workshop resource. It is not an official
> GitHub Universe or GitHub event website and is not endorsed by GitHub.
> GitHub, GitHub Copilot, and the Octocat are trademarks of GitHub, Inc.
> Public-facing mascot use requires approval from GitHub's Brand & Marketing
> Design team under the
> [mascot guidelines](https://brand.github.com/graphic-elements/mascots).
