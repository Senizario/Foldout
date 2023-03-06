# Foldout

Attribute

This attribute agroup the variables in the inspector, for example:

[Foldout("Components/Debugger")]
[SerializeField] private Image connectionImg;

[Foldout("Components")]
[SerializeField] private Button connectionBtn;

[Foldout("Components/Debugger")]
[SerializeField] private TMP_Text connectionTxt;

The inspector will show a Components folder that will contain the connnection Btn and other folder with the other two variables.

This attribute create a MonoBehaviour and ScriptableObject class to save the user data, but this class will not compiled, like a editor class.

This attribute does not work for a non MonoBehaviour or ScriptableObject classes.
