[![build](https://github.com/haru/redmine_code_review/actions/workflows/build.yml/badge.svg)](https://github.com/haru/redmine_code_review/actions/workflows/build.yml)
[![Maintainability](https://api.codeclimate.com/v1/badges/adc7bcbf7bfd8e80a97b/maintainability)](https://codeclimate.com/github/haru/redmine_code_review/maintainability)
[![codecov](https://codecov.io/gh/haru/redmine_code_review/branch/develop/graph/badge.svg?token=37CJ55KBUU)](https://codecov.io/gh/haru/redmine_code_review)

# Redmine Code Review Plugin

This is a plugin for Redmine which lets you annotate source code within the repository browser.

http://www.r-labs.org/wiki/r-labs/Code_Review

## Plugin installation

1. Copy the plugin directory into the plugins directory

2. Migrate plugin:
   rake redmine:plugins:migrate RAILS_ENV=production

3. Start Redmine

4. Add code review module into your project.

5. Go to code review setting tab in the project setting page and select tracker.

6. Go to "Roles and permissions" and add "Code Review" permissions to the roles you want to see/edit/manage code reviews.

## Language contributors

* de.yml - Michael Diederich, Sebastian Bernhard
* fr.yml - Thomas M, fcrespel
* hu.yml - Péter Major, József Kószó
* ko.yml - Ki-yong Kim, Ki Won Kim
* nl.yml - Stefan Verstege
* pt-br.yml - Alessandro Hecht
* zh.yml - Marshall Wu
* zh-tw.yml - Andrew Liu
* ru.yml - Mykhaylo Sorochan
* sk.yml - Milan Freml
* es.yml - Ignacio Carrera
* pl.yml - Rafal Grzymkowski
* sv.yml - André Jonsson
* bg.yml - Ivan Cenov, jwalkerbg
