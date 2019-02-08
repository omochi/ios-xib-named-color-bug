ViewController.innocentView is set red color for background in XIB.
This red is named color which is defined in XCAsset as `redColor`. 
Even if I changed this to blue in `viewDidLoad`, it is displaying as red.
When I change named color to ordinal static color in XIB,
logic in `viewDidLoad` will run expectedly.
