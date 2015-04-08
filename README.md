### A tool to make it easy to find OS projects to contribute to

```open_source_toolkit search --language="ruby" --popularity="medium"  --commitment="beginner"```

Default filter: listing them in order of health (are they maintained, are issues worked through or ignored, etc.)
TODO: useful heuristic for if the project is healthy or not.

#### search
options:
  * language
  * popularity
		TODO: need to look up partitioning of stars for projects on GH to get an accurate heirarchy
		eg: --popularity="medium" would query for projects between 20-200 starts
  * commitment
		TODO: create reasonable heuristic/what data to crunch
		eg: that have any issues tagged as "newbie" or "beginner", and if none, could look at the experience of most committers to get an idea if there are many newbies working on it (maybe a more advanced heuristic, maybe not useful).

### future ideas:
- needs_maintainers -- register a repo for if you're looking for a maintainer, make it easy to connect and take over a repo, min star/watchers limit
- repo_health -- if I'm considering looking at contributing to project X, is it maintained?  Do people care?  Issue to resolution ratio? etc.
- find_collaborators -- a search to find profiles of people looking for specific OS work
- looking_for -- register what you're looking for to show up in the find_collaborators search
