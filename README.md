# ImagePicker
 Handled UIImagePickerController and Camera Permission
 
 # How to use
 
    var imagePicker: ImagePicker!

    override func viewDidLoad() {
        super.viewDidLoad()
        self.imagePicker = ImagePicker(presentationController: self, delegate: self)
     
    }
    
     @IBAction func didClickImagePicker(_ sender: UIButton) {
        self.imagePicker.present(from: sender)
    }
    
 <br/>
 <img src="https://github.com/Magesh-S1314/ImagePicker/blob/master/Simulator%20Screen%20Shot%20-%20iPhone%20SE%20(2nd%20generation)%20-%202021-01-23%20at%2013.37.20.png" width="250">
