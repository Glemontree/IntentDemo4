# IntentDemo4
This Demo shows how to return data to the original Activity

1. use startActivityForResult(intent, requestCode) instead of startActivity()
2. you should override the onActivityResult() function to get the return data from the second Activity
3. In the second Activity, create a new Intent, and use putExtra() function()  to put data in the intent, and use setResult() function to set the
   result, then finish the second Activity and the onActivityResult() function will be called!
