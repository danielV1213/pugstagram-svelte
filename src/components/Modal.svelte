<div class="modal">
  <div class="modal-overlay" />
  <slot />
</div>

<style>
  .modal {
    position: relative;
  }
  .modal-overlay {
    background-color: rgba(0, 0, 0, 0.7);
    position: fixed;
    width: 100%;
    height: 100%;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    z-index: 8;
    cursor: pointer;
  }
</style>
