# Borrar-un-view-controller-de-un-ui-tab-bar-controller

```

if let tabBarController = self.tabBarController {
    let indexToRemove = 3
    if indexToRemove < tabBarController.viewControllers?.count {
        var viewControllers = tabBarController.viewControllers
        viewControllers?.remove(at: indexToRemove)
        tabBarController.viewControllers = viewControllers
    }
}

```
