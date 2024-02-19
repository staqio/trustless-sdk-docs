//[trustless](../../index.md)/[com.trustless.utils](index.md)/[runAsync](run-async.md)

# runAsync

[kotlin]\
fun &lt;[T](run-async.md)&gt; [runAsync](run-async.md)(callback: [AsyncCallback](-async-callback/index.md)&lt;[T](run-async.md)&gt;?, operation: suspend () -&gt; [T](run-async.md))

This function is used to turn suspended function into callback based

runAsync(callback) {     TrustlessSDK.instance.getCards() }
