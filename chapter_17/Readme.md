> Can you show me all the files in slash temp slash foo?

I would run `find /tmp/foo -name "*" -print` and it returned "/tmp/foo" and "/tmp/foo/sample.txt"

> What log files are in your log directory?

I would run `find /tmp/log -name "*.log" -print` and it would return "/tmp/log//production.log"