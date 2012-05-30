## Overview

This project aims to provide boilerplate file templates for RubyMotion, similar to those which can be generated with XCode.

## Installation

    gem install thor
    git clone https://andyw8@github.com/andyw8/rubymotion_generators.git

## Usage

    cd rubymotion_generators
    thor motion:generate view welcome #=> app/welcome_view.rb
    thor motion:generate table_view_controller people #=> generates app/people_table_view_controller.rb

## Current Limitations

The output files are created the rubymotion_generators project so you'll need to copy them into your app. This will not be necessary once the project becomes a gem.

## To Do

- Turn into a gem so it can be run from inside an existing project
- UIViewController
- UITableViewCell
- iPad option
- Tests
- Option to specify file path