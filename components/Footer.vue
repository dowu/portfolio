<template>
  <footer class="footer">
    <p>
      If you want to follow my journey you can also visit me on
      <a
        href="https://www.linkedin.com/in/dowu/"
        target="_blank"
        rel="noopener noreferrer"
        >LinkedIn </a
      >,
      <a
        href="https://twitter.com/wurmdo"
        target="_blank"
        rel="noopener noreferrer"
        >Twitter </a
      >,
      <a
        href="https://github.com/dowu/dowu"
        target="_blank"
        rel="noopener noreferrer"
        >GitHub
      </a>
      and
      <a
        href="https://dribbble.com/Dowu"
        target="_blank"
        rel="noopener noreferrer"
        >Dribbble </a
      >. You can also send a mail to
      <a href="mailto:me@dowu.xyz" target="_blank" rel="noopener noreferrer"
        >me@dowu.xyz
      </a>.
    </p>
  </footer>
</template>

<style lang="scss" scoped>
.footer {
  margin: 0 0 136px 0;
  @include padding(0 32px);
  @include flex(center, flex-start, column);
  @include viewport(sm) {
    margin-bottom: 32px;
  }
}
</style>
