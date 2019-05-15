# Swift 5.0 

```Swift
class SwitchViewController: UIViewController {
   
   @IBOutlet weak var bulbImageView: UIImageView!
   
   @IBOutlet weak var testSwitch: UISwitch!
   
   @IBAction func stateChanged(_ sender: UISwitch) {
        bulbImageView.isHighlighted = sender.isOn
   }        
}
```

```
class SwitchViewController: UIViewController {
   
   @IBOutlet weak var bulbImageView: UIImageView!
   
   @IBOutlet weak var testSwitch: UISwitch!
   
   @IBAction func stateChanged(_ sender: UISwitch) {
        bulbImageView.isHighlighted = sender.isOn
   }        
}
```