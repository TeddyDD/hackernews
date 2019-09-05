# hn
Hacker News without leaving your terminal.

### Installation
Copy the shell script to a folder in your `$PATH`.

### Usage
```
$ hn -h

  NAME:
    hn -- Hacker News without leaving your terminal.

  SYNOPSIS:
    hn [-c] [-h] [-l LIMIT]

  OPTIONS:
    -c    Colorize the output.
    -r    Show lobste.rs instead of Hacker News
    -l    Limit to LIMIT articles.
    -h    prints a summary of the help options.

  EXAMPLES:
    hn
      GoDaddy supports SOPA, redditor proposes "Move your Domain Day"
      http://www.reddit.com/r/politics/comments/nmnie/godaddy_supports_sopa_im_transferring_51_domains/

      StackOverflow also planning to switch from GoDaddy due to SOPA concerns.
      http://meta.stackoverflow.com/q/116891/1588

      GoDaddy has not withdrawn its official congressional support for SOPA
      http://www.reddit.com/r/technology/comments/npair/godaddy_has_not_withdrawn_its_official/

      ...

    hn -l 1
      GoDaddy supports SOPA, redditor proposes "Move your Domain Day"
      http://www.reddit.com/r/politics/comments/nmnie/godaddy_supports_sopa_im_transferring_51_domains/
```
