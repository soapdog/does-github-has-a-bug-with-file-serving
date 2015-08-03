#Github Bug With File Serving

Apparently github has a bug serving plain text files that use markdown but have a header. This format of file is very popular with static generators and these headers usually carry metadata about the page itself.

You can compare

http://soapdog.github.io/does-github-has-a-bug-with-file-serving/test.txt

with

https://github.com/soapdog/does-github-has-a-bug-with-file-serving/blob/gh-pages/test.txt

To see the top of the file vanish when serving.
