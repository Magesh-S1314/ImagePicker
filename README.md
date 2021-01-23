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
