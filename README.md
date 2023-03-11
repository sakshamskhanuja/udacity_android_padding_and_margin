## Padding and Margin

### About

The application uses ```android:padding``` attribute to introduce spacing among Views.

```xml
<?xml version="1.0" encoding="utf-8"?>
<LinearLayout ...>

    ...

    <!-- You're invited! TextView -->
    <TextView
        style="@style/Text"
        android:paddingTop="@dimen/paddingDefault"
        android:paddingBottom="@dimen/paddingSmall"
        android:text="@string/big_text"
        android:textSize="@dimen/bigText" />

    <!-- Bonfire at the beach TextView -->
    <TextView
        style="@style/Text"
        android:paddingBottom="@dimen/paddingDefault"
        android:text="@string/small_text"
        android:textSize="@dimen/heading" />
</LinearLayout>
```

### Screenshots

| Device      | Virtual | OS        | API | Orientation                                                                                                         |
|-------------|---------|-----------|-----|---------------------------------------------------------------------------------------------------------------------|
| Pixel 6 Pro | Yes     | Android Q | 29  | [Portrait](https://user-images.githubusercontent.com/122201501/224496283-17a7167e-a249-42b4-9c61-f929c62f0f56.png)  |
| Pixel 6 Pro | Yes     | Android Q | 29  | [Landscape](https://user-images.githubusercontent.com/122201501/224496279-ac2e4b84-5cec-4037-8be6-a354d6181c94.png) |
