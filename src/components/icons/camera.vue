<template functional>
  <svg :width="props.size || '20px'" :height="props.size || '20px'" viewBox="0 0 22 20" version="1.1" xmlns:xlink="http://www.w3.org/1999/xlink" aria-label="camera"><path d="M8 1L6.17 3H3c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2h-3.17L14 1H8zm3 15c-2.76 0-5-2.24-5-5s2.24-5 5-5 5 2.24 5 5-2.24 5-5 5z" :fill="props.dark ? '#fff' : (props.color || '#000')" fill-rule="nonzero" stroke="#DDD" stroke-width="1"></path></svg>
</template>
