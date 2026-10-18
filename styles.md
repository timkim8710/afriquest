/* Custom CSS Extensions for AfriQuest */

/* Hide Scrollbar for clean tab scrolling */
.no-scrollbar::-webkit-scrollbar {
  display: none;
}
.no-scrollbar {
  -ms-overflow-style: none;
  scrollbar-width: none;
}

/* Low Bandwidth Data-Saver Styles */
.data-saver-active img,
.data-saver-active video,
.data-saver-active canvas {
  display: none !important;
}

.data-saver-active .data-saver-hide {
  display: none !important;
}

/* Custom Scrollbar for dark code views */
pre::-webkit-scrollbar {
  height: 6px;
}
pre::-webkit-scrollbar-thumb {
  background: #d97706;
  border-radius: 4px;
}