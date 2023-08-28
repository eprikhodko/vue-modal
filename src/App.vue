<template>
  <div class="container">
    <header class="header">
      <p class="logo">[ morda-morda ]</p>
      <button type="button" class="button-primary">Open modal</button>
    </header>

    <main class="main-content">
      <div class="cta-block-container">
        <div class="cta-block">
          <h1 class="cta-title">Ready to Build a Modal Component?</h1>
          <p class="cta-text">
            Unlock the power of Vue 3 by crafting your own custom modal. This essential UI element
            can elevate the user experience on any website or application.
          </p>

          <button type="button" class="button-primary">Open modal</button>
        </div>
      </div>

      <!-- <div class="text-content">
        <p>
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Curabitur nibh nibh, vulputate in
          semper vel, ullamcorper id dolor. Nam sollicitudin dignissim ipsum id elementum. Nam
          aliquam sapien vel consequat molestie. Orci varius natoque penatibus et magnis dis
          parturient montes, nascetur ridiculus mus. Sed non ligula a leo aliquam varius. Aenean
          suscipit, quam id vestibulum condimentum, tellus dolor egestas lectus, ut ullamcorper
          purus nisl in neque. Curabitur sed volutpat libero.
        </p>

        <p>
          Integer mi turpis, eleifend faucibus quam eget, tincidunt molestie mauris. Proin ut felis
          vitae tellus hendrerit vestibulum vel vel arcu. Etiam cursus, tellus in cursus pretium,
          velit diam pretium lectus, ut dapibus purus erat nec enim. Praesent viverra velit diam, eu
          aliquet enim consequat nec. Etiam volutpat sed velit sed luctus. Quisque diam metus,
          sollicitudin vel eros a, pretium viverra odio. Vivamus quis ex ut nunc vehicula mattis.
          Vestibulum convallis aliquet ex, sit amet pulvinar est hendrerit ut. Curabitur ullamcorper
          maximus ligula, nec fermentum lorem auctor non. Donec blandit sed quam non malesuada. Nam
          facilisis, elit sodales lacinia varius, orci sem imperdiet risus, non blandit nisi neque
          ut neque. Nullam eget pellentesque purus. Suspendisse potenti. Suspendisse id enim a nisi
          vehicula rhoncus. Nullam eleifend laoreet maximus.
        </p>

        <p>
          Nunc quis malesuada velit. Nam et fringilla risus. Sed eros sem, molestie tristique elit
          sed, tincidunt feugiat ante. In vitae est quis enim mattis luctus at ut enim. Fusce in
          fringilla nulla, vitae tempor sapien. Vivamus fringilla mauris sem, a pharetra nisi
          venenatis in. Praesent arcu enim, maximus in mauris nec, venenatis semper lectus. Sed
          vulputate ornare ligula, eu mattis sapien ultricies sed. Nam laoreet erat id urna rutrum
          convallis. Curabitur tincidunt eu ex eu blandit. Aliquam non tristique purus. Ut non
          varius ligula. Sed facilisis nisi sit amet consectetur euismod. Aenean id neque auctor,
          feugiat ante placerat, accumsan tellus. Maecenas et enim bibendum, bibendum libero eu,
          finibus velit. Quisque ac orci consequat, vestibulum erat non, aliquet elit.
        </p>

        <p>
          Nam dictum nisl vitae vehicula hendrerit. Aenean et ultrices nulla, eget dictum nunc.
          Pellentesque turpis augue, faucibus id libero non, tristique mattis velit. Duis egestas
          porta augue, a egestas sapien. Nullam odio massa, porttitor nec nunc egestas, viverra
          sollicitudin ex. Cras consectetur velit eu nunc consectetur, non rhoncus nibh lobortis.
          Proin dapibus orci quis pulvinar ullamcorper. Vestibulum tincidunt turpis sed mi venenatis
          malesuada. Nullam lacus tortor, sagittis tincidunt tincidunt nec, ornare sit amet odio.
          Curabitur finibus sed ex id ornare. Aliquam vitae ultrices nibh. Cras viverra sit amet
          nibh eu viverra. Etiam pulvinar ut velit id tristique.
        </p>

        <p>
          Proin diam enim, consectetur id velit sit amet, blandit hendrerit arcu. Quisque porttitor
          orci ac mauris aliquam fermentum. Aenean vel laoreet diam, sit amet ultrices felis.
          Praesent venenatis dictum justo, ut semper eros elementum et. Vivamus metus tortor,
          vehicula vel sapien nec, pulvinar mollis enim. Morbi bibendum magna nec porttitor blandit.
          Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis
          egestas. Sed vitae viverra metus. Sed a urna sed lorem tincidunt efficitur. Ut interdum
          eros vel dui interdum facilisis. Vivamus ullamcorper, leo nec mattis iaculis, magna tellus
          laoreet nisi, sit amet blandit felis neque sit amet felis. Sed efficitur mauris nibh, nec
          tristique nisi hendrerit quis. Vestibulum suscipit odio metus. Ut quis turpis neque.
          Praesent eget lectus eu nisi dapibus tincidunt.
        </p>

        <p>
          Etiam porta justo at lobortis eleifend. Nulla facilisi. Aenean condimentum commodo felis,
          ac consectetur metus maximus at. Vivamus porta fringilla consequat. Nullam aliquet nec
          nisi feugiat fringilla. Sed in lectus posuere justo hendrerit mattis. Mauris sit amet
          rutrum magna, ut dapibus quam. Quisque pharetra venenatis libero, at tempor metus
          convallis eu. Nam tincidunt tellus sit amet nisi lobortis aliquet.
        </p>

        <p>
          Vestibulum luctus ante magna, at porttitor odio pretium id. Vestibulum dapibus elementum
          laoreet. Phasellus malesuada nec nisi quis suscipit. Pellentesque tempus, odio a porttitor
          euismod, nibh tortor pretium enim, ut ultricies libero diam et est. Nullam bibendum, est
          sed porta porttitor, tortor orci fermentum ipsum, vitae luctus elit felis in libero.
          Praesent ullamcorper semper pellentesque. Phasellus at sem vel magna malesuada sodales a
          in nisl. Mauris volutpat consequat ultrices. Nulla scelerisque turpis et urna suscipit,
          vel tempor ipsum elementum. Etiam lectus purus, lacinia vitae risus in, molestie interdum
          ipsum. Phasellus sed lorem mollis, egestas nisl blandit, condimentum est. Aenean vitae est
          pellentesque, viverra nisl dignissim, mollis mauris. Duis feugiat vitae arcu quis
          accumsan. Fusce consequat suscipit augue non placerat.
        </p>

        <p>
          Integer aliquam feugiat augue pharetra aliquam. Phasellus et quam lobortis, ornare quam
          et, dignissim dui. Etiam a est mollis, accumsan quam sed, sodales tortor. Nunc in elit ac
          arcu bibendum malesuada. Vestibulum varius blandit odio, nec tristique velit cursus sed.
          Suspendisse in enim vehicula, facilisis velit at, dignissim diam. Vivamus quis luctus
          urna. Sed eget commodo orci, at lobortis quam. Duis convallis risus viverra, euismod justo
          id, sagittis enim. Nullam aliquam nec arcu non rhoncus.
        </p>

        <p>
          Nulla facilisi. Aliquam nec diam porttitor, commodo tortor et, pretium ante. Nunc sed
          aliquam tellus. Maecenas a egestas arcu. Praesent non libero lacus. Vestibulum efficitur
          interdum feugiat. Suspendisse augue quam, dignissim vitae viverra quis, egestas ut mauris.
        </p>

        <p>
          Pellentesque eu libero facilisis, ultricies enim ut, mollis arcu. Sed tempus, sem at
          feugiat porta, augue purus facilisis nibh, vitae vestibulum est ante at diam. Aliquam
          elementum vehicula lobortis. Sed turpis sapien, eleifend vitae interdum porta, aliquam in
          ipsum. Duis ultricies mauris nec leo tempor, id mattis metus lacinia. Quisque sagittis ex
          turpis, tempus molestie dui pretium vitae. Donec nec egestas lorem. Quisque vel vehicula
          mauris, nec cursus nulla.
        </p>

        <p>
          Pellentesque ex tortor, commodo quis fermentum quis, sodales ac erat. Mauris mi augue,
          gravida quis blandit dictum, ultricies vitae est. Nullam dictum, libero at ultrices
          dictum, ipsum risus accumsan eros, bibendum venenatis ipsum libero ut nisi. Donec ante
          erat, interdum faucibus tortor non, hendrerit vestibulum nisl. Suspendisse efficitur quam
          nunc. Quisque sagittis purus nisi, quis vulputate lorem elementum sit amet. Suspendisse
          tempor sem arcu, non volutpat dui scelerisque at. Pellentesque sed blandit elit, in
          vehicula ipsum. Aliquam erat volutpat. Integer arcu urna, scelerisque eget aliquet eu,
          varius vel ligula. In ullamcorper, diam vitae dapibus feugiat, diam felis sagittis quam,
          ut euismod neque erat ut justo. Aenean maximus metus ornare pretium cursus. Praesent
          pellentesque, sapien ac tristique eleifend, risus tortor dictum purus, varius tristique
          lectus nisl a tortor. Fusce eget quam dignissim, finibus tellus et, molestie massa. Duis
          dignissim non elit eu tristique. Ut ut nunc placerat, egestas dolor a, rutrum dui.
        </p>

        <p>
          In hac habitasse platea dictumst. Vestibulum at nisi in sapien maximus auctor. Nulla
          facilisi. Sed egestas urna metus, id scelerisque enim ultricies nec. Quisque et velit
          risus. Fusce porta magna nunc, id congue diam posuere ac. Integer facilisis iaculis
          ligula, consectetur rhoncus ipsum pulvinar at. Duis eu suscipit ex. Nullam ultrices, erat
          sed placerat pretium, erat ante consequat tortor, vitae suscipit purus libero eu ipsum.
          Vivamus pellentesque id arcu id volutpat. Pellentesque sit amet viverra leo. Suspendisse
          at facilisis turpis. Aenean congue nisl hendrerit tellus blandit, id pulvinar arcu
          facilisis. Proin et suscipit diam, ac accumsan ligula. Curabitur at orci quis elit
          interdum luctus ac a dolor.
        </p>

        <p>
          Etiam sed dignissim lorem. Nunc tristique ante ac volutpat bibendum. Suspendisse blandit,
          lectus at ullamcorper luctus, metus diam sollicitudin risus, a cursus sapien ligula id
          quam. In in vulputate ex, maximus sollicitudin odio. Etiam condimentum lacus sit amet
          egestas bibendum. Proin sed augue auctor, condimentum metus quis, mattis erat. Donec
          interdum magna velit, quis dapibus dui sollicitudin ac. Etiam vel felis maximus sapien
          tristique laoreet ut rhoncus risus. Cras scelerisque congue mi et hendrerit.
        </p>

        <p>
          Cras non justo a lacus varius eleifend. Quisque pellentesque vitae mi et mollis. Nulla
          egestas pulvinar erat quis elementum. Aenean sed ex vulputate, aliquet ligula at, tempor
          orci. Morbi eget mi sed felis convallis dictum. Duis ultricies non odio ac elementum.
          Curabitur mattis lacus sit amet ultrices pharetra. Duis rutrum mattis nunc, id luctus
          ipsum lacinia vel. Pellentesque magna sem, laoreet vitae feugiat id, mattis id ligula.
          Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos
          himenaeos. Nunc egestas accumsan odio, id finibus ligula tempor quis.
        </p>

        <p>
          Quisque dapibus porta massa ut cursus. Suspendisse convallis nibh eu diam suscipit iaculis
          vel id eros. Sed tristique tempus vulputate. Pellentesque eget mi a leo molestie
          fermentum. Quisque mauris erat, luctus a condimentum et, blandit vel libero. Nam porta
          neque quis ex volutpat, pellentesque sollicitudin diam faucibus. Morbi pretium nisi ut
          mauris malesuada auctor. Ut consequat nisl lectus, id eleifend metus aliquet tempus. Fusce
          fringilla, purus ut aliquet varius, ante tortor dapibus lacus, sed tincidunt turpis risus
          sed nisi. Aenean quis purus at ipsum egestas interdum. Cras hendrerit viverra scelerisque.
          In sed dictum dolor. Donec tincidunt nisl id augue dictum, eu molestie quam pellentesque.
          Sed scelerisque nulla felis, ac sodales sem convallis ut. Nulla sollicitudin nulla eu
          lectus malesuada faucibus.
        </p>
      </div> -->
    </main>
    <footer>site footer</footer>
  </div>
</template>

<style>
.container {
  max-width: 1440px;
  width: 100%;
  display: flex;
  flex-direction: column;
  margin: auto;
}

.header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 0 112px;
}

.cta-block-container {
  margin-bottom: 96px;
}

.cta-block {
  padding: 112px 56px;
  background-color: #fff0e2;
  border-radius: 24px;
  background-image: url("./assets/img/tuborg-cat.png");
  background-repeat: no-repeat;
  background-position: bottom right;
}

.cta-title {
  font-size: 48px;
  line-height: 56px;
  max-width: 500px;
}

.cta-text {
  font-size: 20px;
  /* line-height: 28px; */
  font-weight: 600;
  max-width: 540px;
}

.main-content {
  padding: 0 56px;
}

.text-content {
  max-width: 1024px;
  margin: auto;
}

.logo {
  text-transform: uppercase;
  font-weight: 900;
  font-size: 24px;
  margin: 0;
  padding: 20px 0;
}

.button-primary {
  background-color: #ff6490;
  border: none;
  color: #fff;
  border-radius: 8px;
  padding: 12px 24px;
  font-size: 20px;
  font-weight: 600;
  cursor: pointer;
}
</style>
