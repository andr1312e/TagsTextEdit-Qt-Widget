# TabsTextEdit-Qt-Widget

This is a simple, animated, high-performance input widget with textarea field. Simple code, few stl algorithms and no c++17 features, just for qt beginners.

Use https://github.com/nicktrandafil/tags if you need lineEdit field and new stl features

Auto split input text into tags by comma, Space or Enter key. 

Auto scroll area.

Auto prevent duplicate tags. If you don't need this feature remove `m_tagsPresenter->IsEditedTextHasDuplicate()` in `keyPressEvent` method

How to use:

1. Copy TagsPresenter TagsLineEditWidget and Tag into your project
2. App gui-private to .pro file, in linux you should add package to your repo
3. Add TagsLineEditWidget into layout or show it
4. Connect to signals if it nessessary

![1](.//images//1.gif)

UML Diagram:

![2](.//images//uml.png)
