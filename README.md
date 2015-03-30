# PathPropertyDrawer

- Unityのファイルパス/ディレクトリパス用のCustumPropertyDrawerです。
- String型の変数につけることで、テキストボックス隣にパス参照ボタンが表示されます。

```csharp
using UnityEngine;
using System.Collections;

public class SampleClass : MonoBehaviour {

	public string m_NoAttribute;

	[FilePath]
	public string m_FilePath;

	[FolderPath]
	public string m_FolderPath;


}
```
