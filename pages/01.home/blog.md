---
title: Home
body_classes: 'header-image fullwidth'
content:
    items: '@self.children'
    limit: 5
    order:
        by: date
        dir: desc
    pagination: '1'
hide_sidebar: false
post_icon: calendar-o
continue_link_as_button: false
hide_git_sync_repo_link: false
modular_content:
    items: '@self.modular'
    order:
        by: default
        custom:
            - _important-reminders
            - _unit-preparations
feed:
    description: 'Grav CMS Open Course Hub Description'
    limit: 10
---

