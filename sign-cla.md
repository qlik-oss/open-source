Sign the CLA
=============

This page outlines the (relatively simple) process of signing a Qlik Contributor License Agreement ("CLA"). If you are wondering why we require you to sign this agreement, please visit the [CLA Rationale](cla-rationale.md) page.

The steps needed are:

1. Read the [Contributor License Agreement](cla-v1.0.md).

2. Sign up for a [GitHub account](https://github.com/join) if you do not already have one.

3. Make a Pull Request by following the section called "Making the Pull Request."

4. Send us an email by following the section called "Sending the Email."

5. Wait for a Qlik R&D member to merge your Pull Request, which is our way of officially accepting your electronic signing of the CLA. Feel free to start sending Pull Requests to our projects while you wait!


---

Making the Pull Request
-----------------------

Pull Requests are at the center of contributing to projects on GitHub. If you are new to this, [GitHub provides an excellent guide on how that works](https://help.github.com/articles/using-pull-requests).

Your Pull Request should contain a single, new file in the `contributors/` directory. The filename should be your GitHub User ID, suffixed with `.md`.

As an example, if your GitHub User ID is `ExampleGitHubUser`, the filename would be `ExampleGitHubUser.md`. The full path to your new file would be `contributors/ExampleGitHubUser.md`.

Use the template below and fill in the bracketed text with the appropriate information.

### Legend

* `[date]`: Replace with the current date in `YYYY-mm-dd` form, example: `2016-11-01` for November 1st, 2016.
* `[name]`: Your full, legal name.
* `[githubid]`: Your GitHub User ID.

### Template

```
[date]

By introducing this file I hereby agree to the terms of the Qlik R&D Contributors License
Agreement, version 1.0, with MD5 checksum: e4ed5b420a8c9400390a55ac12dad65b.

I furthermore declare that I am authorized and able to make this agreement.

Signed,

[name]
https://github.com/[githubid]
```

You can confirm the MD5 checksum of the CLA by running the `md5` program on the [cla-v1.0.md](cla-v1.0.md) file.

On Linux, Mac, or Windows (using the Git Bash):

```
$ md5 cla-v1.0.md
```

If the output from this command is different from what you can see in the template above, do not sign it and *let us know*.


* * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * *

Sending the Email
-----------------

To make sure we have the required legal information for this electronic signing, we also need a bit of private information. This information is not shared with any third-party organization and may only be used in the case of legal disputes.

### Contact

To: [sign-cla@qlik.com](mailto:sign-cla@qlik.com)

Subject: CLA

Email body: Use template below

### Legend

* `[pullrequesturl]`: The full URL to your submitted Pull Request.
* `[name]`: Your full legal name.
* `[githubid]`: Your GitHub User ID.
* `[address]`: Your full physical contact address.
* `[phone]`: Your full phone number (including country code).

### Template

```
I submitted a CLA Pull Request here: [pullrequesturl]

Signed,

[name]
https://github.com/[githubid]
[address]
[phone]
```
