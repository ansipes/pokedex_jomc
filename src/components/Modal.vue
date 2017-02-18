<template>

  <div class="modal" :class="{'is-active' : isActive }">
      <div class="modal-background"></div>
      <div class="modal-content box">
        <div class="container">
            <div class="tile is-ancestor">
              <div class="tile is-vertical is-12">
                <div class="tile">
                  <thumb
                    :name="name"
                    :image="image">
                  </thumb>
                  <trait
                    :type="type"
                    :ability="ability">
                  </trait>
                  <metric
                    :height="height"
                    :weight="weight">
                  </metric>
                </div>
                <stat
                  :hitPoints="hitPoints"
                  :attack="attack"
                  :defense="defense"
                  :speed="speed"
                  :sAttack="sAttack"
                  :sDefense="sDefense">
                </stat>
              </div>
            </div>
          </div>
      </div>
      <button @click="closeModal" class="modal-close"></button>

    </div>



</template>


<script>

import Thumb from './Thumb.vue';
import Trait from './Trait.vue';
import Metric from './Metric.vue';
import Stat from './Stat.vue';

export default {
  name: 'modal',
  components: { Thumb, Trait, Metric, Stat },
  props: [
  'name',
  'image',
  'type',
  'ability',
  'height',
  'weight',
  'hitPoints',
  'attack',
  'defense',
  'speed',
  'sAttack',
  'sDefense',
  'isActive'
  ],
  data() {
    return {
      isActive: true
    }
  },
  methods: {
    closeModal: function() {
      this.isActive = false;
    }
  }
}

</script>
