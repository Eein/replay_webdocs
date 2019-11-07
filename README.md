# FPGA Arcade

[VuePress](https://vuepress.vuejs.org/) based documentation for FPGA Arcade projects.

For local development:

```
yarn install
yarn run docs:dev
```

# Formatting Notes

## Alerts

You can use alerts (containers0 to draw the users attention to useful hints
or potential for damage. Keep in mind it's the title is that determines the
note level, "tip", "warning" and "danger" are for the container type only.

```
::: tip Tip
This is for little nuggets of optional information. Perhaps a keyboard
shortcut to achieve a task quicker.
:::

::: tip Note
This is for drawing attention to information that whilst not important
may help the user save time.
:::
```

Tip and Note should be items that might help a user save time but
where ignoring will cause no lasting harm.

```
::: warning Take Care
Use to draw attention to information that should not be ignored. Ignoring
this may cause data loss or physical damage.
:::
```

Warning and Danger are unlikely to be needed but have been included for completeness.

```
::: danger Warning
Use to warn about possibility of personal injury.
:::

::: danger Danger
Use to warn about the possibility of serious or fatal injuries.
:::
```

Refer to the VuePress site for further information on containers.