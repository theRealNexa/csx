# CSX

Open repository of academic resources (lecture notes, past questions, textbooks and more) for the Nexa Faculty Platform, maintained by The Nexa Network.

## How it works

- Resources are uploaded by platform admins through the Nexa Faculty Platform.
- Each upload opens a **pull request** in this repository.
- Repository maintainers review the pull request and **merge** it to approve the file.
- Once merged, the file appears in the platform's library for students to download.

## Structure

```
resources/
  <COURSE-CODE>/
    <id>-<title>.pdf
```

Files are placed here automatically by the platform. Please don't rename or move files in `resources/` by hand, as the platform links to them by path.

## For maintainers

- Check that each PDF is the right course and resource type, is readable, and is safe to share publicly.
- Reject anything you aren't sure the contributor has the right to share.
- Merge to approve. Close the pull request to reject.

## Note

This repository is public, so anyone can read the files here directly, without logging in to the platform.

## License

See [LICENSE](LICENSE).
