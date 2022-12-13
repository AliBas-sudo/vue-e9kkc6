template>

  <div class="videojs">

    <h1>{{ title }}</h1>

    <div class="video-inner-container">

      <video

        id="vid1"

        controls

        preload="auto"width="640"height="264"

        class="video-js vjs-fluid vjs-default-skin vjs-big-play-centered"

        data-setup='{}'>

          <source:src=src :type=type </source>

      </video>

    </div>

  </div>

</template>

<script>

  import 'videojs-youtube/dist/Youtube.min.js';

  import 'video.js/dist/video-js.min.css';

  import 'video.js/dist/video.min.js';

  export default {

    name:'VideoJS',

    props: ['title', 'src', 'type']

}

</script>