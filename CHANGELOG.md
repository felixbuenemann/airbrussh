## Next release

* Your contribution here!

## 0.4.1 (2015-05-06)

* Fix `Marshal.dump` warnings by removing `deep_copy` workaround that it is no longer needed for the latest SSHKit ([#10](https://github.com/mattbrictson/airbrussh/issues/10)).

## 0.4.0 (2015-05-03)

* Changes to ensure compatibility with the upcoming version of SSHKit ([ec3122b](https://github.com/mattbrictson/airbrussh/commit/ec3122b101de53f2304723da842d5c8b6f70f4f3)).
* Explicitly specify UTF-8 encoding for source files, for Ruby 1.9.3 compatibility ([#9](https://github.com/mattbrictson/airbrussh/issues/9)).

## 0.3.0 (2015-03-28)

* New `config.banner` option allows startup message to be disabled or changed (suggestion from [@justindowning](https://github.com/justindowning))
* New `config.command_output` option gives full control of whether airbrussh shows or hides the stderr and stdout data received from remote commands; see the usage section of the README for further explanation (suggestion from [@carlesso](https://github.com/carlesso))

## 0.2.1 (2015-03-02)

* Un-pin SSHKit dependency now that SSHKit 1.7.1 has been released.

## 0.2.0 (2015-03-02)

* Pin SSHKit dependency at `~> 1.6.1` to avoid a [bug in 1.7.0](https://github.com/capistrano/sshkit/issues/226) that causes command exit statuses to be omitted from the log.

## 0.0.1 (2015-02-19)

* Initial release