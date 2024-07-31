# InputBox

An input box for winforms

## Basic Usage

```cs
using WinFormsInputBox;
InputBoxResult result = InputBox.Show("text", "title", defaultValue);

if(result.ReturnCode == DialogResult.OK) Console.WriteLine(result.Text);
```