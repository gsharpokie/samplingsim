# How Many Do You Need to Ask?

A sampling simulator. Students survey an imaginary campus of 10,000 students, choosing who to ask (a random sample or a convenience sample) and how many (25 to 1,600). Every survey adds a dot to a chart, so students can see sampling error, why bigger samples help less and less, and why a large biased sample is still wrong. By Gwen Sharp, as a companion to Chapter 2 (Research Methods) of *A Sociology Experiment*.

**Live site:** https://gsharpokie.github.io/samplingsim/

## What it does

- **Who do you ask?** A random sample, or whoever is in the library on a Friday night.
- **How many?** 25, 100, 400, or 1,600 students.
- **Run the survey** once or 50 times. Each result is a dot on a 0–100% scale. Random samples are circles and library samples are squares.
- **The true answer stays hidden** until the student selects “Show the true answer,” so they first have to decide how much to trust their own results.
- **Things to try:** four short experiments. **What you’re seeing** explains sampling error, margin of error, convenience samples, and the 1936 *Literary Digest* poll, followed by discussion questions.

## For instructors

- Everything is simulated in the student’s browser. Each student gets different dots, which makes comparing results part of the lesson. Nothing is saved or sent anywhere.
- The campus is invented: 38% of all students work 20+ hours a week, and 21% of students in the library on Friday night do.

## Changing the scenario

Open `index.html` on GitHub, select the pencil icon, and near the top of the `<script>` section change:

- `TRUE_P = 0.38` (the true share) and `LIB_P = 0.21` (the share in the convenience sample),
- `SIZES = [25, 100, 400, 1600]` (the sample sizes offered).

The wording of the scenario (campus, jobs, library) is plain text in the page and can be edited the same way.

## Turning on the site (one time)

Go to **Settings → Pages**. Under **Build and deployment**, set **Source** to **Deploy from a branch**, choose the **main** branch and the **/ (root)** folder, and select **Save**. Keep Issues turned on so the “Suggest a correction” link works.

## Source

Squire, Peverill. 1988. “Why the 1936 Literary Digest Poll Failed.” *Public Opinion Quarterly* 52(1): 125–133.

## Author

Created by Gwen Sharp ([@gsharpokie](https://x.com/gsharpokie)).

## License

© 2026 Gwen Sharp. Licensed under [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/): you may share and adapt it for noncommercial purposes with credit. See [LICENSE](LICENSE).
