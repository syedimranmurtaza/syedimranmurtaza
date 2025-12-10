<h2 align="left">I'm Syed Imran Murtaza, I don’t just design websites, I design how audience feels.</h2>

<div align="center">

<table>
<tr>
<td>

<pre style="font-family:Fira Code, monospace; font-size:14px; color:#00FF9D; background:#0d0d0d; padding:16px; border-radius:8px; width:420px;">
public class Portfolio extends Experience {
    private static final String VISION = "Design that feels alive";

    public static void main(String[] args) {
        new Portfolio().launch();
    }

    public void launch() {
        renderUI(createLayout(buildFlow(generateEmotion())));
    }

    private Emotion generateEmotion() {
        return new Emotion.Builder()
            .setDepth(100)
            .setColorTheory("Vivid")
            .setUserFocus("High")
            .build();
    }

    private Flow buildFlow(Emotion emotion) {
        return new Flow(emotion).optimize().animate().stabilize();
    }

    private Layout createLayout(Flow flow) {
        return new Layout(flow)
            .addLayers(12)
            .addMicroInteractions()
            .finalizeDesign();
    }
}
</pre>

</td>

<td align="center" style="padding-left:20px;">

<img 
  src="https://i.pinimg.com/originals/68/33/8f/68338f7c63fa408acc8df33f349cdedd.gif" 
  height="240"
  style="border-radius:10px;"
/>

</td>
</tr>
</table>

</div>
