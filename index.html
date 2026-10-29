<!DOCTYPE html>
<html lang="en" class="h-full bg-slate-900">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no, viewport-fit=cover" />
  <meta name="apple-mobile-web-app-capable" content="yes" />
  <meta name="apple-mobile-web-app-status-bar-style" content="black-translucent" />
  <meta name="theme-color" content="#0f172a" />
  <title>Borewell QuickQuote • Mobile Only</title>
  <script src="https://cdn.tailwindcss.com/3.4.17"></script>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@500;600;700;800&family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Plus Jakarta Sans', -apple-system, BlinkMacSystemFont, sans-serif;
      -webkit-tap-highlight-color: transparent;
      user-select: none;
      -webkit-user-select: none;
    }
    input, textarea {
      user-select: auto;
      -webkit-user-select: auto;
    }
    .pb-safe {
      padding-bottom: calc(5.5rem + env(safe-area-inset-bottom, 16px));
    }
    .no-scrollbar::-webkit-scrollbar {
      display: none;
    }
    .no-scrollbar {
      -ms-overflow-style: none;
      scrollbar-width: none;
    }
    input[type="number"]::-webkit-inner-spin-button,
    input[type="number"]::-webkit-outer-spin-button {
      -webkit-appearance: none;
      margin: 0;
    }
    input[type="number"] {
      -moz-appearance: textfield;
    }
    .pulse-ring {
      animation: pulseAnimation 1.6s infinite cubic-bezier(0.4, 0, 0.6, 1);
    }
    @keyframes pulseAnimation {
      0%, 100% { box-shadow: 0 0 0 0 rgba(239, 68, 68, 0.6); }
      50% { box-shadow: 0 0 0 10px rgba(239, 68, 68, 0); }
    }
  </style>
</head>
<body class="h-full bg-slate-950 text-slate-900 flex justify-center antialiased">

  <!-- Mobile Viewport Shell (Dedicated Phone Layout: 100% width up to 430px) -->
  <div class="w-full max-w-md min-h-screen bg-slate-50 flex flex-col shadow-2xl relative">

    <!-- Mobile Top Header Bar -->
    <header class="bg-slate-900 text-white sticky top-0 z-30 px-3.5 pt-3 pb-2.5 border-b border-slate-800 shadow-md">
      <div class="flex items-center justify-between gap-2">
        <div class="flex items-center gap-2 min-w-0">
          <div class="w-8 h-8 rounded-xl bg-gradient-to-tr from-sky-600 to-cyan-400 flex items-center justify-center shadow-md shrink-0">
            <svg class="w-4 h-4 text-white" fill="none" stroke="currentColor" stroke-width="2.3" viewBox="0 0 24 24">
              <path stroke-linecap="round" stroke-linejoin="round" d="M12 3v18m0 0l-4-4m4 4l4-4M5 7h14M7 11h10" />
            </svg>
          </div>
          <div class="truncate">
            <h1 id="headerCompanyName" class="text-xs sm:text-sm font-bold tracking-tight text-white leading-tight truncate">Borewell QuickQuote</h1>
            <p class="text-[10px] font-medium text-sky-300 flex items-center gap-1">
              <span class="w-1.5 h-1.5 rounded-full bg-emerald-400 animate-pulse"></span>
              Phone Call Estimator
            </p>
          </div>
        </div>

        <div class="flex items-center gap-1.5 shrink-0">
          <button id="btnVoiceQuick" type="button" class="flex items-center gap-1 bg-sky-500 hover:bg-sky-400 active:scale-95 text-slate-950 font-black text-xs px-2.5 py-1.5 rounded-xl transition shadow">
            <svg class="w-3.5 h-3.5 text-slate-950" fill="none" stroke="currentColor" stroke-width="2.4" viewBox="0 0 24 24">
              <path stroke-linecap="round" stroke-linejoin="round" d="M12 18.75a6 6 0 006-6v-1.5m-6 7.5a6 6 0 01-6-6v-1.5m6 7.5v3.75m-3.75 0h7.5M12 15.75a3 3 0 01-3-3V4.5a3 3 0 116 0v8.25a3 3 0 01-3 3z" />
            </svg>
            <span id="voiceBtnLabel">Voice Input</span>
          </button>
        </div>
      </div>
    </header>

    <!-- STICKY MOBILE LIVE PRICE HUD: Always visible while scrolling on phone! -->
    <div id="mobileStickyPriceHud" class="sticky top-[52px] z-20 bg-slate-950/95 backdrop-blur-md text-white px-3.5 py-2.5 border-b border-slate-800 shadow-md">
      <div class="flex items-center justify-between">
        <div>
          <div class="flex items-center gap-1.5">
            <span class="text-[9px] font-bold uppercase tracking-wider text-slate-400">Total Quote</span>
            <span id="originalPriceStrike" class="text-[10px] line-through text-slate-400 hidden">₹0</span>
            <span id="hudDiscountBadge" class="text-[9px] font-black px-1.5 py-0.2 rounded bg-amber-400 text-slate-950 hidden">DISCOUNT</span>
          </div>
          <div class="flex items-baseline gap-1.5 mt-0.5">
            <span id="finalPriceDisplay" class="text-2xl font-black text-emerald-400 tracking-tight leading-none">₹18,285</span>
            <span id="effectivePerFootDisplay" class="text-[11px] font-bold text-slate-300">₹33.25 / ft</span>
          </div>
          <p id="summaryHeadline" class="text-[10px] text-slate-400 font-medium truncate mt-0.5 max-w-[200px]">550 ft • Good (Moderate)</p>
        </div>

        <div class="flex items-center gap-1.5">
          <!-- One-Tap WhatsApp Share on Phone -->
          <button id="btnQuickWhatsAppTop" type="button" class="flex items-center gap-1 bg-emerald-500 active:scale-90 text-slate-950 font-black text-xs px-2.5 py-2 rounded-xl shadow transition" title="Share quote to WhatsApp">
            <svg class="w-3.5 h-3.5 fill-current" viewBox="0 0 24 24"><path d="M.057 24l1.687-6.163c-1.041-1.804-1.588-3.849-1.587-5.946.003-6.556 5.338-11.891 11.893-11.891 3.181.001 6.167 1.24 8.413 3.488 2.245 2.248 3.481 5.236 3.48 8.414-.003 6.557-5.338 11.892-11.893 11.892-1.99-.001-3.951-.5-5.688-1.448l-6.305 1.654zm6.597-3.807c1.676.995 3.276 1.591 5.392 1.592 5.448 0 9.886-4.434 9.889-9.885.002-5.462-4.415-9.89-9.881-9.892-5.452 0-9.887 4.434-9.889 9.884-.001 2.225.651 3.891 1.746 5.634l-.999 3.648 3.742-.981zm11.387-5.464c-.074-.124-.272-.198-.57-.347-.297-.149-1.758-.868-2.031-.967-.272-.099-.47-.149-.669.149-.198.297-.768.967-.941 1.165-.173.198-.347.223-.644.074-.297-.149-1.255-.462-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.297-.347.446-.521.151-.172.2-.296.3-.495.099-.198.05-.372-.025-.521-.075-.148-.669-1.611-.916-2.206-.242-.579-.487-.501-.669-.51l-.57-.01c-.198 0-.52.074-.792.372s-1.04 1.016-1.04 2.479 1.065 2.876 1.213 3.074c.149.198 2.095 3.2 5.076 4.487.709.306 1.263.489 1.694.626.712.226 1.36.194 1.872.118.571-.085 1.758-.719 2.006-1.413.248-.695.248-1.29.173-1.414z"/></svg>
            <span class="text-[11px]">Send</span>
          </button>
          <!-- Speak Aloud -->
          <button id="btnSpeakEstimate" type="button" class="p-2 rounded-xl bg-slate-800 active:bg-slate-700 text-sky-400 transition" title="Read Estimate Aloud">
            <svg class="w-4 h-4" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24">
              <path stroke-linecap="round" stroke-linejoin="round" d="M15.536 8.464a5 5 0 010 7.072m2.828-9.9a9 9 0 010 12.728M5.586 15H4a1 1 0 01-1-1v-4a1 1 0 011-1h1.586l4.707-4.707C10.923 3.663 12 4.109 12 5v14c0 .891-1.077 1.337-1.707.707L5.586 15z" />
            </svg>
          </button>
        </div>
      </div>
    </div>

    <!-- Active Voice Banner -->
    <div id="voiceStatusBanner" class="hidden bg-sky-950 text-sky-100 border-b border-sky-800 px-3.5 py-2 z-20">
      <div class="flex items-center justify-between gap-2">
        <div class="flex items-center gap-2 min-w-0">
          <span class="w-2.5 h-2.5 rounded-full bg-red-500 pulse-ring shrink-0"></span>
          <p id="voiceTranscriptText" class="text-[11px] font-semibold truncate">Listening... Speak depth & quality</p>
        </div>
        <div class="flex items-center gap-1.5 shrink-0">
          <button type="button" id="btnSimulateVoice550" class="text-[10px] bg-sky-800 active:bg-sky-700 text-white px-2 py-0.5 rounded-lg font-bold">Try Demo: "550ft Moderate Cheap"</button>
          <button type="button" id="btnCloseVoiceBanner" class="text-[11px] text-sky-300 px-1 py-0.5">Close</button>
        </div>
      </div>
    </div>

    <!-- Toast Notification -->
    <div id="toastBanner" class="fixed top-14 left-1/2 -translate-x-1/2 z-50 hidden bg-slate-900/95 text-white px-4 py-2 rounded-full shadow-2xl border border-slate-700 text-xs font-bold flex items-center gap-2 pointer-events-none">
      <span class="w-2 h-2 rounded-full bg-emerald-400"></span>
      <span id="toastMessage">Done!</span>
    </div>

    <!-- MAIN SCROLLABLE APP BODY (Optimized for One-Thumb Phone Use) -->
    <main class="flex-1 px-3 py-3 pb-safe space-y-3">

      <!-- ==================== TAB 1: PHONE-OPTIMIZED ESTIMATOR ==================== -->
      <section id="tab-calculator" class="space-y-3">

        <!-- 1. Borewell Depth Card -->
        <div class="bg-white rounded-2xl p-3.5 shadow-sm border border-slate-200/90">
          <div class="flex items-center justify-between mb-2">
            <label for="inputDepth" class="text-[11px] font-black text-slate-700 uppercase tracking-wider flex items-center gap-1.5">
              <span class="w-4 h-4 rounded-full bg-sky-600 text-white inline-flex items-center justify-center text-[10px] font-black">1</span>
              Borewell Depth
            </label>
            <span class="text-[10px] font-bold text-sky-600">Tap Presets or Type</span>
          </div>

          <!-- Big Stepper + Number Input -->
          <div class="flex items-center gap-2">
            <button type="button" id="btnDepthMinus50" class="w-11 h-11 rounded-xl bg-slate-100 active:bg-slate-200 text-slate-800 font-black text-base flex items-center justify-center border border-slate-200 shrink-0">
              -50
            </button>
            <div class="relative flex-1">
              <input id="inputDepth" type="number" inputmode="numeric" pattern="[0-9]*" min="1" max="5000" step="1" value="550"
                class="w-full text-center text-2xl font-black text-slate-900 bg-slate-50 border-2 border-slate-200 focus:border-sky-500 focus:bg-white rounded-xl py-1.5 px-2 outline-none transition" />
              <span class="absolute right-3 top-2.5 text-xs font-black text-slate-400 pointer-events-none">FT</span>
            </div>
            <button type="button" id="btnDepthPlus50" class="w-11 h-11 rounded-xl bg-slate-100 active:bg-slate-200 text-slate-800 font-black text-base flex items-center justify-center border border-slate-200 shrink-0">
              +50
            </button>
          </div>

          <!-- Horizontal Scrollable Preset Depth Pills -->
          <div class="flex items-center gap-1.5 overflow-x-auto no-scrollbar pt-2 pb-0.5">
            <button type="button" data-depth="100" class="depth-chip shrink-0 px-2.5 py-1.5 rounded-xl text-xs font-bold bg-slate-100 active:scale-95 text-slate-700 border border-slate-200">100 ft</button>
            <button type="button" data-depth="150" class="depth-chip shrink-0 px-2.5 py-1.5 rounded-xl text-xs font-bold bg-slate-100 active:scale-95 text-slate-700 border border-slate-200">150 ft</button>
            <button type="button" data-depth="250" class="depth-chip shrink-0 px-2.5 py-1.5 rounded-xl text-xs font-bold bg-slate-100 active:scale-95 text-slate-700 border border-slate-200">250 ft</button>
            <button type="button" data-depth="350" class="depth-chip shrink-0 px-2.5 py-1.5 rounded-xl text-xs font-bold bg-slate-100 active:scale-95 text-slate-700 border border-slate-200">350 ft</button>
            <button type="button" data-depth="500" class="depth-chip shrink-0 px-2.5 py-1.5 rounded-xl text-xs font-bold bg-slate-100 active:scale-95 text-slate-700 border border-slate-200">500 ft</button>
            <button type="button" data-depth="550" class="depth-chip shrink-0 px-2.5 py-1.5 rounded-xl text-xs font-black bg-sky-600 active:scale-95 text-white border border-sky-600">550 ft</button>
            <button type="button" data-depth="700" class="depth-chip shrink-0 px-2.5 py-1.5 rounded-xl text-xs font-bold bg-slate-100 active:scale-95 text-slate-700 border border-slate-200">700 ft</button>
            <button type="button" data-depth="1000" class="depth-chip shrink-0 px-2.5 py-1.5 rounded-xl text-xs font-bold bg-slate-100 active:scale-95 text-slate-700 border border-slate-200">1000 ft</button>
          </div>
        </div>

        <!-- 2. Pipe Quality Selector (Thumb-Sized Mobile Cards) -->
        <div class="bg-white rounded-2xl p-3.5 shadow-sm border border-slate-200/90">
          <div class="flex items-center justify-between mb-2">
            <span class="text-[11px] font-black text-slate-700 uppercase tracking-wider flex items-center gap-1.5">
              <span class="w-4 h-4 rounded-full bg-sky-600 text-white inline-flex items-center justify-center text-[10px] font-black">2</span>
              Pipe & Bore Quality
            </span>
            <button type="button" id="btnJumpPipeSettings" class="text-xs font-bold text-sky-600 hover:text-sky-700">+ Edit Qualities</button>
          </div>
          <!-- Stack of Big Mobile Cards with Instant Math -->
          <div id="qualitySelectorGrid" class="space-y-1.5">
            <!-- Rendered by JS -->
          </div>
        </div>

        <!-- 3. Labour Option Selector (Side-by-Side Mobile Toggle Buttons) -->
        <div class="bg-white rounded-2xl p-3.5 shadow-sm border border-slate-200/90">
          <div class="flex items-center justify-between mb-2">
            <span class="text-[11px] font-black text-slate-700 uppercase tracking-wider flex items-center gap-1.5">
              <span class="w-4 h-4 rounded-full bg-sky-600 text-white inline-flex items-center justify-center text-[10px] font-black">3</span>
              Labour Option
            </span>
            <button type="button" id="btnJumpLabourSettings" class="text-xs font-bold text-sky-600 hover:text-sky-700">+ Edit Labour</button>
          </div>
          <div id="labourSelectorGrid" class="grid grid-cols-2 gap-2">
            <!-- Rendered by JS -->
          </div>
        </div>

        <!-- 4. Quick Customer Discount & Rounding Bar -->
        <div class="bg-white rounded-2xl p-3.5 shadow-sm border border-slate-200/90 space-y-2">
          <div class="flex items-center justify-between">
            <label for="inputDiscountValue" class="text-[11px] font-black text-slate-800 uppercase tracking-wider flex items-center gap-1.5">
              <span class="w-4 h-4 rounded-full bg-amber-500 text-slate-950 inline-flex items-center justify-center text-[10px] font-black">%</span>
              Customer Discount
            </label>
            <div class="inline-flex rounded-lg bg-slate-100 p-0.5 border border-slate-200">
              <button type="button" id="btnDiscModeFlat" class="px-2 py-0.5 text-[10px] font-black rounded-md bg-amber-500 text-slate-950 transition">₹ Flat</button>
              <button type="button" id="btnDiscModePct" class="px-2 py-0.5 text-[10px] font-bold rounded-md text-slate-600 transition">% Off</button>
            </div>
          </div>

          <div class="flex items-center gap-2">
            <div class="relative flex-1">
              <span id="discPrefix" class="absolute left-2.5 top-2 text-xs font-black text-slate-400">₹</span>
              <input id="inputDiscountValue" type="number" inputmode="numeric" pattern="[0-9]*" min="0" step="50" value="0"
                class="w-full bg-slate-50 border border-slate-200 focus:border-amber-500 focus:bg-white rounded-xl pl-6 pr-2 py-1.5 text-xs font-black text-slate-900 outline-none"
                placeholder="Discount..." />
            </div>
            <button type="button" id="btnRoundPrice" class="shrink-0 bg-slate-100 active:bg-slate-200 text-xs font-bold px-2.5 py-1.5 rounded-xl border border-slate-200 text-slate-800">
              Round ₹500
            </button>
            <button type="button" id="btnClearDiscount" class="shrink-0 bg-slate-100 active:bg-slate-200 text-xs font-bold px-2 py-1.5 rounded-xl border border-slate-200 text-slate-500">
              Clear
            </button>
          </div>

          <!-- Quick Discount Preset Chips -->
          <div class="flex items-center gap-1.5 overflow-x-auto no-scrollbar">
            <button type="button" data-disc-chip="0" class="disc-preset-chip px-2 py-1 rounded-lg text-[10px] font-bold bg-slate-100 active:scale-95 text-slate-700 border border-slate-200">₹0</button>
            <button type="button" data-disc-chip="500" class="disc-preset-chip px-2 py-1 rounded-lg text-[10px] font-bold bg-slate-100 active:scale-95 text-slate-700 border border-slate-200">-₹500</button>
            <button type="button" data-disc-chip="1000" class="disc-preset-chip px-2 py-1 rounded-lg text-[10px] font-bold bg-slate-100 active:scale-95 text-slate-700 border border-slate-200">-₹1,000</button>
            <button type="button" data-disc-chip="1500" class="disc-preset-chip px-2 py-1 rounded-lg text-[10px] font-bold bg-slate-100 active:scale-95 text-slate-700 border border-slate-200">-₹1,500</button>
            <button type="button" data-disc-pct-chip="5" class="disc-preset-chip px-2 py-1 rounded-lg text-[10px] font-bold bg-slate-100 active:scale-95 text-slate-700 border border-slate-200">5% Off</button>
            <button type="button" data-disc-pct-chip="10" class="disc-preset-chip px-2 py-1 rounded-lg text-[10px] font-bold bg-slate-100 active:scale-95 text-slate-700 border border-slate-200">10% Off</button>
          </div>
        </div>

        <!-- 5. Collapsible Full Breakdown & Company Margin -->
        <div class="bg-white rounded-2xl shadow-sm border border-slate-200/90 overflow-hidden">
          <button type="button" id="btnToggleBreakdown" class="w-full p-3 flex items-center justify-between text-left active:bg-slate-50 transition">
            <div class="flex items-center gap-1.5">
              <span class="text-[11px] font-black text-slate-800 uppercase tracking-wider">Detailed Math Breakdown</span>
              <span id="breakdownPillCount" class="text-[9px] font-bold bg-slate-100 text-slate-600 px-1.5 py-0.5 rounded-full">3 Items</span>
            </div>
            <div class="flex items-center gap-1 text-sky-600 text-xs font-bold">
              <span id="breakdownToggleLabel">Show Details</span>
              <svg id="breakdownToggleIcon" class="w-3.5 h-3.5 transform transition-transform" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M19 9l-7 7-7-7"/></svg>
            </div>
          </button>

          <div id="breakdownContainer" class="hidden px-3.5 pb-3.5 border-t border-slate-100 space-y-2 pt-2.5 text-xs">
            <div class="flex items-center justify-between py-1 border-b border-slate-100">
              <div>
                <span class="font-bold text-slate-800">Pipe Cost</span>
                <span id="breakdownPipeFormula" class="block text-[10px] text-slate-500">550 ft × ₹10/ft</span>
              </div>
              <span id="breakdownPipeTotal" class="font-black text-slate-900 text-xs sm:text-sm">₹5,500</span>
            </div>

            <div class="flex items-center justify-between py-1 border-b border-slate-100">
              <div>
                <span class="font-bold text-slate-800">Labour Cost</span>
                <span id="breakdownLabourFormula" class="block text-[10px] text-slate-500">550 ft × ₹20/ft</span>
              </div>
              <span id="breakdownLabourTotal" class="font-black text-slate-900 text-xs sm:text-sm">₹11,000</span>
            </div>

            <div class="py-1 border-b border-slate-100">
              <div class="flex items-center justify-between">
                <span class="font-bold text-slate-800">Misc Costs (<span id="activeMiscCount">0</span> active)</span>
                <span id="breakdownMiscTotal" class="font-black text-slate-900 text-xs sm:text-sm">₹1,785</span>
              </div>
              <div id="breakdownMiscList" class="mt-1 space-y-1 pl-2 border-l-2 border-slate-200 text-[10px] text-slate-500">
                <!-- misc lines -->
              </div>
            </div>

            <!-- Optional Company Extra on Call -->
            <div class="pt-1.5">
              <label for="inputCompanyExtra" class="block text-[10px] font-bold text-slate-600 mb-1">Company Extra / Fee & Caller Info (Optional)</label>
              <div class="flex items-center gap-1.5">
                <input id="inputCompanyExtra" type="number" inputmode="numeric" pattern="[0-9]*" min="0" step="100" value="0"
                  class="flex-1 bg-slate-50 border border-slate-200 rounded-xl px-2.5 py-1.5 text-xs font-bold text-slate-800 outline-none" placeholder="Extra ₹" />
                <input id="inputCustomerName" type="text"
                  class="flex-1 bg-slate-50 border border-slate-200 rounded-xl px-2.5 py-1.5 text-xs text-slate-800 outline-none" placeholder="Caller Name" />
              </div>
            </div>

            <div id="rowCompanyExtra" class="flex items-center justify-between py-1 border-t border-slate-100 hidden">
              <span class="font-bold text-slate-700">Company Margin</span>
              <span id="breakdownCompanyExtra" class="font-black text-sky-700">+₹0</span>
            </div>

            <div id="rowDiscountApplied" class="flex items-center justify-between py-1 border-t border-slate-100 hidden">
              <span class="font-bold text-amber-600">Discount Given</span>
              <span id="breakdownDiscountAmount" class="font-black text-amber-600">-₹0</span>
            </div>
          </div>
        </div>

        <!-- Big Mobile Action Buttons -->
        <div class="grid grid-cols-2 gap-2 pt-1">
          <button type="button" id="btnCopyQuote" class="w-full flex items-center justify-center gap-1.5 bg-emerald-500 active:scale-95 text-slate-950 font-black text-xs py-3 px-3 rounded-2xl shadow transition">
            <svg class="w-4 h-4 fill-current" viewBox="0 0 24 24"><path d="M.057 24l1.687-6.163c-1.041-1.804-1.588-3.849-1.587-5.946.003-6.556 5.338-11.891 11.893-11.891 3.181.001 6.167 1.24 8.413 3.488 2.245 2.248 3.481 5.236 3.48 8.414-.003 6.557-5.338 11.892-11.893 11.892-1.99-.001-3.951-.5-5.688-1.448l-6.305 1.654zm6.597-3.807c1.676.995 3.276 1.591 5.392 1.592 5.448 0 9.886-4.434 9.889-9.885.002-5.462-4.415-9.89-9.881-9.892-5.452 0-9.887 4.434-9.889 9.884-.001 2.225.651 3.891 1.746 5.634l-.999 3.648 3.742-.981zm11.387-5.464c-.074-.124-.272-.198-.57-.347-.297-.149-1.758-.868-2.031-.967-.272-.099-.47-.149-.669.149-.198.297-.768.967-.941 1.165-.173.198-.347.223-.644.074-.297-.149-1.255-.462-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.297-.347.446-.521.151-.172.2-.296.3-.495.099-.198.05-.372-.025-.521-.075-.148-.669-1.611-.916-2.206-.242-.579-.487-.501-.669-.51l-.57-.01c-.198 0-.52.074-.792.372s-1.04 1.016-1.04 2.479 1.065 2.876 1.213 3.074c.149.198 2.095 3.2 5.076 4.487.709.306 1.263.489 1.694.626.712.226 1.36.194 1.872.118.571-.085 1.758-.719 2.006-1.413.248-.695.248-1.29.173-1.414z"/></svg>
            <span>Copy / WhatsApp</span>
          </button>
          <button type="button" id="btnSaveQuote" class="w-full flex items-center justify-center gap-1.5 bg-sky-500 active:scale-95 text-slate-950 font-black text-xs py-3 px-3 rounded-2xl shadow transition">
            <svg class="w-4 h-4" fill="none" stroke="currentColor" stroke-width="2.3" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M5 13l4 4L19 7"/></svg>
            <span>Save Call Quote</span>
          </button>
        </div>

      </section>

      <!-- ==================== TAB 2: PHONE SETTINGS ==================== -->
      <section id="tab-settings" class="hidden space-y-3">
        <div class="bg-white rounded-2xl p-3.5 shadow-sm border border-slate-200">
          <div class="flex items-center justify-between mb-1">
            <div>
              <h2 class="text-xs sm:text-sm font-black text-slate-900">Rates & Settings</h2>
              <p class="text-[10px] text-slate-500">Edit, add, or delete rates instantly.</p>
            </div>
            <button type="button" id="btnLoadPromptExample" class="text-[10px] font-bold bg-sky-50 active:bg-sky-100 text-sky-700 border border-sky-200 px-2 py-1 rounded-xl">
              Load ₹10 Pipe / ₹20 Labour Demo
            </button>
          </div>
        </div>

        <!-- 1. Pipe Quality Settings -->
        <div class="bg-white rounded-2xl p-3.5 shadow-sm border border-slate-200 space-y-2.5">
          <div class="flex items-center justify-between">
            <h3 class="text-[11px] font-black uppercase tracking-wider text-slate-700">1. Pipe Quality Tiers</h3>
            <span class="text-[10px] text-slate-400">× Borewell Depth</span>
          </div>

          <div id="settingsQualitiesList" class="space-y-2">
            <!-- Rendered by JS -->
          </div>

          <!-- Add Quality on Mobile -->
          <div class="bg-slate-50 rounded-xl p-2.5 border border-slate-200 space-y-2">
            <span class="text-[10px] font-bold text-slate-700 block">+ Add New Quality Tier</span>
            <input id="newQualityName" type="text" placeholder="Tier Name (e.g. Good Quality)" class="w-full bg-white border border-slate-200 rounded-xl px-2.5 py-1.5 text-xs font-semibold" />
            <input id="newQualitySubtitle" type="text" placeholder="Description (e.g. Medium PVC)" class="w-full bg-white border border-slate-200 rounded-xl px-2.5 py-1.5 text-[11px] text-slate-600" />
            <div class="flex items-center gap-1.5">
              <input id="newQualityRate" type="number" inputmode="numeric" min="0" step="1" placeholder="₹ per foot" class="flex-1 bg-white border border-slate-200 rounded-xl px-2.5 py-1.5 text-xs font-bold" />
              <button type="button" id="btnAddQuality" class="bg-sky-600 active:bg-sky-500 text-white font-bold text-xs px-3 py-1.5 rounded-xl shrink-0">
                + Add Tier
              </button>
            </div>
          </div>
        </div>

        <!-- 2. Labour Settings -->
        <div class="bg-white rounded-2xl p-3.5 shadow-sm border border-slate-200 space-y-2.5">
          <div class="flex items-center justify-between">
            <h3 class="text-[11px] font-black uppercase tracking-wider text-slate-700">2. Labour Cost Options</h3>
            <span class="text-[10px] text-slate-400">Cheap vs Expensive</span>
          </div>

          <div id="settingsLabourList" class="space-y-2">
            <!-- Rendered by JS -->
          </div>

          <!-- Add Labour on Mobile -->
          <div class="bg-slate-50 rounded-xl p-2.5 border border-slate-200 space-y-2">
            <span class="text-[10px] font-bold text-slate-700 block">+ Add New Labour Option</span>
            <input id="newLabourName" type="text" placeholder="Labour Name (e.g. Cheap Labour)" class="w-full bg-white border border-slate-200 rounded-xl px-2.5 py-1.5 text-xs font-semibold" />
            <input id="newLabourNote" type="text" placeholder="Description (e.g. Local Crew)" class="w-full bg-white border border-slate-200 rounded-xl px-2.5 py-1.5 text-[11px] text-slate-600" />
            <div class="flex items-center gap-1.5">
              <input id="newLabourRate" type="number" inputmode="numeric" min="0" step="1" placeholder="₹ per foot" class="flex-1 bg-white border border-slate-200 rounded-xl px-2.5 py-1.5 text-xs font-bold" />
              <button type="button" id="btnAddLabour" class="bg-sky-600 active:bg-sky-500 text-white font-bold text-xs px-3 py-1.5 rounded-xl shrink-0">
                + Add Labour
              </button>
            </div>
          </div>
        </div>

        <!-- 3. Misc Cost Rules -->
        <div class="bg-white rounded-2xl p-3.5 shadow-sm border border-slate-200 space-y-2.5">
          <div>
            <h3 class="text-[11px] font-black uppercase tracking-wider text-slate-700">3. Miscellaneous Costs</h3>
            <p class="text-[10px] text-slate-500">Per 1 ft, per 100 ft, custom (e.g. 154 ft), or fixed.</p>
          </div>

          <div id="settingsMiscList" class="space-y-2">
            <!-- Rendered by JS -->
          </div>

          <!-- Add Misc Rule on Mobile -->
          <div class="bg-slate-50 rounded-xl p-2.5 border border-slate-200 space-y-2">
            <span class="text-[10px] font-bold text-slate-700 block">Add New Miscellaneous Cost Rule</span>
            <input id="newMiscName" type="text" placeholder="Item Name (e.g. Gravel / Transport)" class="w-full bg-white border border-slate-200 rounded-xl px-2.5 py-1.5 text-xs font-semibold" />
            <select id="newMiscMode" class="w-full bg-white border border-slate-200 rounded-xl px-2 py-1.5 text-xs font-bold">
              <option value="per_ft">Cost Per 1 Foot (₹ × Depth)</option>
              <option value="per_100ft">Cost Per 100 Feet (₹ per 100ft)</option>
              <option value="custom_ft" selected>Custom Feet (₹ for every 154 ft, etc.)</option>
              <option value="fixed">Fixed Cost (₹ Flat Once)</option>
            </select>
            <div class="flex items-center gap-1.5">
              <input id="newMiscRate" type="number" inputmode="numeric" min="0" step="1" placeholder="Cost (₹)" class="flex-1 bg-white border border-slate-200 rounded-xl px-2.5 py-1.5 text-xs font-bold" />
              <div id="newMiscCustomFtWrap" class="flex-1 flex items-center gap-1">
                <span class="text-[10px] text-slate-500">per</span>
                <input id="newMiscUnitFeet" type="number" inputmode="numeric" min="1" step="1" value="154" class="w-full bg-white border border-slate-200 rounded-xl px-1 py-1.5 text-xs font-bold text-center" placeholder="154" />
                <span class="text-[10px] text-slate-500">ft</span>
              </div>
              <button type="button" id="btnAddMisc" class="bg-sky-600 active:bg-sky-500 text-white font-bold text-xs px-3 py-1.5 rounded-xl shrink-0">
                + Add
              </button>
            </div>
          </div>
        </div>

        <!-- 4. Business & Reset Defaults -->
        <div class="bg-white rounded-2xl p-3.5 shadow-sm border border-slate-200 space-y-2.5">
          <h3 class="text-[11px] font-black uppercase tracking-wider text-slate-700">4. Business Profile</h3>
          <div class="space-y-2">
            <div>
              <label for="settingCompanyName" class="block text-[10px] font-bold text-slate-500 mb-0.5">Friend / Company Name</label>
              <input id="settingCompanyName" type="text" class="w-full bg-slate-50 border border-slate-200 rounded-xl px-2.5 py-1.5 text-xs font-bold" />
            </div>
            <div class="grid grid-cols-2 gap-2">
              <div>
                <label for="settingDefaultDepth" class="block text-[10px] font-bold text-slate-500 mb-0.5">Default Depth (ft)</label>
                <input id="settingDefaultDepth" type="number" inputmode="numeric" class="w-full bg-slate-50 border border-slate-200 rounded-xl px-2.5 py-1.5 text-xs font-bold" />
              </div>
              <div>
                <label for="settingDefaultExtra" class="block text-[10px] font-bold text-slate-500 mb-0.5">Default Extra (₹)</label>
                <input id="settingDefaultExtra" type="number" inputmode="numeric" class="w-full bg-slate-50 border border-slate-200 rounded-xl px-2.5 py-1.5 text-xs font-bold" />
              </div>
            </div>
            <div class="flex items-center gap-2 pt-1">
              <button type="button" id="btnSaveBusinessSettings" class="flex-1 bg-slate-900 active:bg-slate-800 text-white text-xs font-bold py-2 rounded-xl">
                Save Business Defaults
              </button>
              <button type="button" id="btnResetDefaults" class="text-xs font-bold text-rose-600 px-3 py-2 rounded-xl border border-rose-200">
                Reset All Settings
              </button>
            </div>
          </div>
        </div>
      </section>

      <!-- ==================== TAB 3: PHONE SIRI & VOICE ==================== -->
      <section id="tab-siri" class="hidden space-y-3">
        <div class="bg-white rounded-2xl p-3.5 shadow-sm border border-slate-200 space-y-3">
          <div class="flex items-center gap-2">
            <span class="w-7 h-7 rounded-xl bg-sky-100 text-sky-700 flex items-center justify-center font-black text-xs">🎙️</span>
            <div>
              <h2 class="text-xs sm:text-sm font-black text-slate-900">Voice Estimator & Apple Siri</h2>
              <p class="text-[10px] text-slate-500">Calculate quotes by speaking during a call.</p>
            </div>
          </div>

          <div class="bg-slate-900 text-white rounded-xl p-3 space-y-2">
            <label for="voiceCommandInput" class="block text-[10px] font-bold text-sky-400 uppercase">Test Voice / Siri Command</label>
            <input id="voiceCommandInput" type="text" value="550 feet moderate quality cheap labour"
              class="w-full bg-slate-800 border border-slate-700 rounded-xl px-3 py-2 text-xs text-white outline-none focus:border-sky-400" />
            <button type="button" id="btnRunVoiceCommand" class="w-full bg-sky-500 active:bg-sky-400 text-slate-950 font-black text-xs py-2 rounded-xl">
              Calculate & Speak Aloud
            </button>
            <div class="flex flex-wrap gap-1 pt-1">
              <button type="button" data-phrase="550 feet moderate quality cheap labour" class="sample-phrase text-[10px] bg-slate-800 text-slate-300 px-2 py-1 rounded-lg border border-slate-700">"550 feet moderate quality cheap labour"</button>
              <button type="button" data-phrase="300 feet best quality expensive labour extra 1000" class="sample-phrase text-[10px] bg-slate-800 text-slate-300 px-2 py-1 rounded-lg border border-slate-700">"300 feet best quality expensive labour extra 1000"</button>
              <button type="button" data-phrase="150 feet good quality cheap labour discount 300" class="sample-phrase text-[10px] bg-slate-800 text-slate-300 px-2 py-1 rounded-lg border border-slate-700">"150 feet good quality cheap labour discount 300"</button>
            </div>
          </div>

          <div class="border-t border-slate-100 pt-3 space-y-2">
            <h3 class="text-xs font-bold text-slate-900">Connect to iPhone Siri Shortcuts</h3>
            <p class="text-[10px] text-slate-500">Copy this URL parameter link to run directly via iOS Shortcuts app:</p>
            <div class="bg-slate-100 rounded-xl p-2.5 flex items-center justify-between gap-2">
              <code id="siriUrlPreview" class="text-[10px] text-slate-800 font-mono truncate">?depth=550&quality=moderate&labour=cheap&speak=1</code>
              <button type="button" id="btnCopySiriUrl" class="bg-slate-900 text-white text-[10px] font-bold px-2.5 py-1.5 rounded-lg shrink-0">
                Copy Siri Link
              </button>
            </div>
          </div>
        </div>
      </section>

      <!-- ==================== TAB 4: SAVED CALL QUOTES ==================== -->
      <section id="tab-history" class="hidden space-y-3">
        <div class="bg-white rounded-2xl p-3.5 shadow-sm border border-slate-200 flex items-center justify-between">
          <div>
            <h2 class="text-xs sm:text-sm font-black text-slate-900">Recent Call Estimates (<span id="savedQuotesHeaderCount">0</span>)</h2>
            <p class="text-[10px] text-slate-500">Saved while talking with customers.</p>
          </div>
          <button type="button" id="btnClearHistory" class="text-[11px] font-bold text-rose-600 px-2.5 py-1 rounded-lg border border-rose-200">
            Clear History
          </button>
        </div>

        <div id="historyListContainer" class="space-y-2">
          <!-- Populated by JS -->
        </div>
      </section>

    </main>

    <!-- NATIVE-STYLE MOBILE BOTTOM NAVIGATION BAR -->
    <nav class="fixed bottom-0 left-0 right-0 z-40 bg-slate-900/95 backdrop-blur-md border-t border-slate-800 flex justify-center shadow-lg">
      <div class="w-full max-w-md flex items-center justify-around px-2 py-2 safe-bottom">
        <button type="button" data-tab="calculator" class="nav-tab flex-1 flex flex-col items-center justify-center py-1 text-sky-400 font-bold transition">
          <svg class="w-5 h-5 mb-0.5" fill="none" stroke="currentColor" stroke-width="2.2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M9 7h6m0 10v-3m-3 3h.01M9 17h.01M9 14h.01M12 14h.01M15 11h.01M12 11h.01M9 11h.01M7 21h10a2 2 0 002-2V5a2 2 0 00-2-2H7a2 2 0 00-2 2v14a2 2 0 002 2z"/></svg>
          <span class="text-[10px] tracking-tight">Estimator</span>
        </button>
        <button type="button" data-tab="settings" class="nav-tab flex-1 flex flex-col items-center justify-center py-1 text-slate-400 hover:text-white font-medium transition">
          <svg class="w-5 h-5 mb-0.5" fill="none" stroke="currentColor" stroke-width="2.2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M10.325 4.317c.426-1.756 2.924-1.756 3.35 0a1.724 1.724 0 002.573 1.066c1.543-.94 3.31.826 2.37 2.37a1.724 1.724 0 001.065 2.572c1.756.426 1.756 2.924 0 3.35a1.724 1.724 0 00-1.066 2.573c.94 1.543-.826 3.31-2.37 2.37a1.724 1.724 0 00-2.572 1.065c-.426 1.756-2.924 1.756-3.35 0a1.724 1.724 0 00-2.573-1.066c-1.543.94-3.31-.826-2.37-2.37a1.724 1.724 0 00-1.065-2.572c-1.756-.426-1.756-2.924 0-3.35a1.724 1.724 0 001.066-2.573c-.94-1.543.826-3.31 2.37-2.37.996.608 2.296.07 2.572-1.065z"/><path stroke-linecap="round" stroke-linejoin="round" d="M15 12a3 3 0 11-6 0 3 3 0 016 0z"/></svg>
          <span class="text-[10px] tracking-tight">Settings & Rates</span>
        </button>
        <button type="button" data-tab="siri" class="nav-tab flex-1 flex flex-col items-center justify-center py-1 text-slate-400 hover:text-white font-medium transition">
          <svg class="w-5 h-5 mb-0.5" fill="none" stroke="currentColor" stroke-width="2.2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M19 11a7 7 0 01-7 7m0 0a7 7 0 01-7-7m7 7v4m0 0H8m4 0h4m-4-8a3 3 0 01-3-3V5a3 3 0 116 0v6a3 3 0 01-3 3z"/></svg>
          <span class="text-[10px] tracking-tight">Siri & Voice</span>
        </button>
        <button type="button" data-tab="history" class="nav-tab flex-1 flex flex-col items-center justify-center py-1 text-slate-400 hover:text-white font-medium transition">
          <svg class="w-5 h-5 mb-0.5" fill="none" stroke="currentColor" stroke-width="2.2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z"/></svg>
          <span class="text-[10px] tracking-tight">Saved Quotes (<span id="savedQuotesCount">0</span>)</span>
        </button>
      </div>
    </nav>

  </div>

  <script>
    (function () {
      const STORAGE_KEY = 'borewell_estimator_v1';

      function getDefaultState() {
        return {
          companyName: 'Borewell QuickQuote',
          defaultDepth: 550,
          defaultExtra: 0,
          qualities: [
            { id: 'q_cheap', name: 'Basic / Economy', subtitle: 'Light PVC Pipe', rate: 10, isDefault: false },
            { id: 'q_moderate', name: 'Good / Moderate', subtitle: 'Budget Friendly • Most Used', rate: 15, isDefault: true },
            { id: 'q_better', name: 'Better / Heavy', subtitle: 'Medium ISI Casing', rate: 22, isDefault: false },
            { id: 'q_best', name: 'Best / Supreme', subtitle: 'Heavy Duty Deep Bore', rate: 30, isDefault: false }
          ],
          labours: [
            { id: 'l_cheap', name: 'Cheap / Standard Labour', note: 'Regular Rig Crew', rate: 20, isDefault: true },
            { id: 'l_expensive', name: 'Expensive / Fast Rig Labour', note: 'High-Power Compressor Rig', rate: 35, isDefault: false }
          ],
          miscRules: [
            { id: 'm_1', name: 'Gravel & Packing', mode: 'per_ft', rate: 2, unitFeet: 1, active: true },
            { id: 'm_2', name: 'Drilling Bit / Diesel Charge', mode: 'per_100ft', rate: 100, unitFeet: 100, active: true },
            { id: 'm_3', name: 'Special Casing / Transport', mode: 'custom_ft', rate: 154, unitFeet: 154, active: true }
          ],
          history: []
        };
      }

      let appState = getDefaultState();
      let currentCalc = {
        depth: 550,
        qualityId: 'q_moderate',
        labourId: 'l_cheap',
        companyExtra: 0,
        customerName: '',
        discountMode: 'flat', // 'flat' or 'pct'
        discountValue: 0
      };

      function loadState() {
        try {
          const raw = localStorage.getItem(STORAGE_KEY);
          if (raw) {
            const parsed = JSON.parse(raw);
            if (parsed && Array.isArray(parsed.qualities) && parsed.qualities.length > 0 && Array.isArray(parsed.labours) && parsed.labours.length > 0) {
              appState = Object.assign(getDefaultState(), parsed);
            }
          }
        } catch (err) {
          console.warn('Storage load fallback:', err);
        }
        const defQ = appState.qualities.find(q => q.isDefault) || appState.qualities[0];
        const defL = appState.labours.find(l => l.isDefault) || appState.labours[0];
        currentCalc.depth = appState.defaultDepth || 550;
        currentCalc.qualityId = defQ ? defQ.id : '';
        currentCalc.labourId = defL ? defL.id : '';
        currentCalc.companyExtra = appState.defaultExtra || 0;
      }

      function saveState() {
        try {
          localStorage.setItem(STORAGE_KEY, JSON.stringify(appState));
        } catch (err) {
          console.warn('Storage save fallback:', err);
        }
      }

      function showToast(msg) {
        const banner = document.getElementById('toastBanner');
        const text = document.getElementById('toastMessage');
        text.textContent = msg;
        banner.classList.remove('hidden');
        clearTimeout(window.__toastTimer);
        window.__toastTimer = setTimeout(() => {
          banner.classList.add('hidden');
        }, 2200);
      }

      function formatINR(num) {
        const n = Math.round((Number(num) || 0) * 100) / 100;
        return '₹' + n.toLocaleString('en-IN', { maximumFractionDigits: 2 });
      }

      function computeMiscItemCost(rule, depth) {
        const d = Math.max(0, Number(depth) || 0);
        const r = Math.max(0, Number(rule.rate) || 0);
        if (rule.mode === 'per_ft') {
          return { cost: d * r, formula: d + ' ft × ₹' + r + '/ft' };
        }
        if (rule.mode === 'per_100ft') {
          const units = d / 100;
          return { cost: units * r, formula: '(' + d + ' / 100 ft) × ₹' + r };
        }
        if (rule.mode === 'custom_ft') {
          const uf = Math.max(1, Number(rule.unitFeet) || 100);
          const units = d / uf;
          return { cost: units * r, formula: '(' + d + ' / ' + uf + ' ft) × ₹' + r };
        }
        return { cost: r, formula: 'Fixed ₹' + r };
      }

      function calculateEstimate() {
        const depth = Math.max(0, Number(currentCalc.depth) || 0);
        const quality = appState.qualities.find(q => q.id === currentCalc.qualityId) || appState.qualities[0];
        const labour = appState.labours.find(l => l.id === currentCalc.labourId) || appState.labours[0];

        const pipeRate = quality ? Number(quality.rate) || 0 : 0;
        const pipeCost = depth * pipeRate;

        const labourRate = labour ? Number(labour.rate) || 0 : 0;
        const labourCost = depth * labourRate;

        let miscTotal = 0;
        const miscDetails = [];
        const activeRules = (appState.miscRules || []).filter(m => m.active);
        activeRules.forEach(rule => {
          const res = computeMiscItemCost(rule, depth);
          miscTotal += res.cost;
          miscDetails.push({
            name: rule.name,
            formula: res.formula,
            cost: res.cost
          });
        });

        const companyExtra = Math.max(0, Number(currentCalc.companyExtra) || 0);
        const grossTotal = pipeCost + labourCost + miscTotal + companyExtra;

        let discountAmount = 0;
        const rawDisc = Math.max(0, Number(currentCalc.discountValue) || 0);
        if (currentCalc.discountMode === 'pct') {
          discountAmount = grossTotal * (Math.min(100, rawDisc) / 100);
        } else {
          discountAmount = Math.min(grossTotal, rawDisc);
        }

        const finalTotal = Math.max(0, grossTotal - discountAmount);
        const perFoot = depth > 0 ? (finalTotal / depth) : 0;

        return {
          depth,
          quality,
          labour,
          pipeRate,
          pipeCost,
          labourRate,
          labourCost,
          miscTotal,
          miscDetails,
          companyExtra,
          grossTotal,
          discountAmount,
          finalTotal,
          perFoot
        };
      }

      function renderCalculator() {
        document.getElementById('headerCompanyName').textContent = appState.companyName || 'Borewell QuickQuote';

        // Depth chips active highlight
        document.querySelectorAll('.depth-chip').forEach(btn => {
          const d = Number(btn.getAttribute('data-depth'));
          if (d === Number(currentCalc.depth)) {
            btn.className = 'depth-chip shrink-0 px-2.5 py-1.5 rounded-xl text-xs font-black bg-sky-600 active:scale-95 text-white border border-sky-600 transition';
          } else {
            btn.className = 'depth-chip shrink-0 px-2.5 py-1.5 rounded-xl text-xs font-bold bg-slate-100 active:scale-95 text-slate-700 border border-slate-200 transition';
          }
        });

        // Render Pipe Quality Selector (Thumb cards with visual checks)
        const qGrid = document.getElementById('qualitySelectorGrid');
        qGrid.innerHTML = '';
        appState.qualities.forEach(q => {
          const selected = q.id === currentCalc.qualityId;
          const card = document.createElement('button');
          card.type = 'button';
          card.className = 'w-full text-left p-2.5 rounded-2xl border-2 transition active:scale-[0.98] flex items-center justify-between gap-2 ' +
            (selected ? 'border-sky-600 bg-sky-50 shadow-sm' : 'border-slate-200 bg-white');
          card.innerHTML = `
            <div class="min-w-0 flex-1">
              <div class="flex items-center gap-1.5 flex-wrap">
                <span class="font-extrabold text-xs text-slate-900">${escapeHtml(q.name)}</span>
                ${q.isDefault ? '<span class="text-[9px] font-black uppercase px-1.5 py-0.2 rounded bg-amber-100 text-amber-900 shrink-0">Most Used</span>' : ''}
              </div>
              <p class="text-[10px] text-slate-500 mt-0.5 truncate">${escapeHtml(q.subtitle || '')}</p>
            </div>
            <div class="text-right shrink-0">
              <div class="text-xs font-black text-sky-700">₹${q.rate}/ft</div>
              <div class="text-[10px] font-bold text-slate-600">${formatINR((Number(currentCalc.depth) || 0) * q.rate)}</div>
            </div>
          `;
          card.addEventListener('click', () => {
            currentCalc.qualityId = q.id;
            renderCalculator();
          });
          qGrid.appendChild(card);
        });

        // Render Labour Selector (2 chunky toggle buttons)
        const lGrid = document.getElementById('labourSelectorGrid');
        lGrid.innerHTML = '';
        appState.labours.forEach(l => {
          const selected = l.id === currentCalc.labourId;
          const card = document.createElement('button');
          card.type = 'button';
          card.className = 'w-full text-left p-2.5 rounded-2xl border-2 transition active:scale-[0.98] flex flex-col justify-between ' +
            (selected ? 'border-sky-600 bg-sky-50 shadow-sm' : 'border-slate-200 bg-white');
          card.innerHTML = `
            <div>
              <span class="font-extrabold text-xs text-slate-900 block leading-tight">${escapeHtml(l.name)}</span>
              <span class="text-[10px] text-slate-500 block truncate mt-0.5">${escapeHtml(l.note || '')}</span>
            </div>
            <div class="mt-1.5 pt-1 border-t border-slate-100 flex items-center justify-between">
              <span class="text-xs font-black text-sky-700">₹${l.rate}/ft</span>
              <span class="text-[10px] font-bold text-slate-600">${formatINR((Number(currentCalc.depth) || 0) * l.rate)}</span>
            </div>
          `;
          card.addEventListener('click', () => {
            currentCalc.labourId = l.id;
            renderCalculator();
          });
          lGrid.appendChild(card);
        });

        // Calculate and update Sticky HUD & Breakdown
        const est = calculateEstimate();
        document.getElementById('finalPriceDisplay').textContent = formatINR(est.finalTotal);
        document.getElementById('effectivePerFootDisplay').textContent = `₹${est.perFoot.toFixed(2)} / ft`;
        document.getElementById('summaryHeadline').textContent =
          `${est.depth} ft • ${est.quality ? est.quality.name : 'Pipe'} • ${est.labour ? est.labour.name : 'Labour'}`;

        const strikeEl = document.getElementById('originalPriceStrike');
        const badgeEl = document.getElementById('hudDiscountBadge');
        if (est.discountAmount > 0) {
          strikeEl.textContent = formatINR(est.grossTotal);
          strikeEl.classList.remove('hidden');
          badgeEl.classList.remove('hidden');
        } else {
          strikeEl.classList.add('hidden');
          badgeEl.classList.add('hidden');
        }

        // Breakdown formulas
        document.getElementById('breakdownPipeFormula').textContent =
          `${est.depth} ft × ₹${est.pipeRate}/ft (${est.quality ? est.quality.name : ''})`;
        document.getElementById('breakdownPipeTotal').textContent = formatINR(est.pipeCost);

        document.getElementById('breakdownLabourFormula').textContent =
          `${est.depth} ft × ₹${est.labourRate}/ft (${est.labour ? est.labour.name : ''})`;
        document.getElementById('breakdownLabourTotal').textContent = formatINR(est.labourCost);

        document.getElementById('activeMiscCount').textContent = est.miscDetails.length;
        document.getElementById('breakdownMiscTotal').textContent = formatINR(est.miscTotal);

        const miscListEl = document.getElementById('breakdownMiscList');
        miscListEl.innerHTML = '';
        est.miscDetails.forEach(m => {
          const row = document.createElement('div');
          row.className = 'flex items-center justify-between';
          row.innerHTML = `<span>${escapeHtml(m.name)} (${escapeHtml(m.formula)})</span><span class="text-slate-800 font-bold">${formatINR(m.cost)}</span>`;
          miscListEl.appendChild(row);
        });

        const rowExtra = document.getElementById('rowCompanyExtra');
        if (est.companyExtra > 0) {
          rowExtra.classList.remove('hidden');
          document.getElementById('breakdownCompanyExtra').textContent = '+' + formatINR(est.companyExtra);
        } else {
          rowExtra.classList.add('hidden');
        }

        const rowDisc = document.getElementById('rowDiscountApplied');
        if (est.discountAmount > 0) {
          rowDisc.classList.remove('hidden');
          document.getElementById('breakdownDiscountAmount').textContent = '-' + formatINR(est.discountAmount);
        } else {
          rowDisc.classList.add('hidden');
        }

        // Update Siri URL preview
        const qSlug = est.quality ? encodeURIComponent(est.quality.name.toLowerCase()) : 'moderate';
        const lSlug = est.labour ? encodeURIComponent(est.labour.name.toLowerCase()) : 'cheap';
        const siriQuery = `?depth=${est.depth}&quality=${qSlug}&labour=${lSlug}&extra=${est.companyExtra}&discount=${est.discountAmount}&speak=1`;
        document.getElementById('siriUrlPreview').textContent = siriQuery;
      }

      function renderSettings() {
        document.getElementById('settingCompanyName').value = appState.companyName || '';
        document.getElementById('settingDefaultDepth').value = appState.defaultDepth || 550;
        document.getElementById('settingDefaultExtra').value = appState.defaultExtra || 0;

        // 1. Qualities list on mobile
        const qContainer = document.getElementById('settingsQualitiesList');
        qContainer.innerHTML = '';
        appState.qualities.forEach((q, idx) => {
          const item = document.createElement('div');
          item.className = 'bg-slate-50 p-2.5 rounded-2xl border border-slate-200 space-y-2';
          item.innerHTML = `
            <div class="flex items-center justify-between gap-2">
              <input type="text" data-q-idx="${idx}" data-field="name" value="${escapeHtml(q.name)}" class="flex-1 bg-white border border-slate-300 rounded-xl px-2 py-1.5 text-xs font-bold" />
              <div class="flex items-center gap-1 shrink-0">
                <span class="text-xs font-bold text-slate-500">₹:</span>
                <input type="number" min="0" step="1" data-q-idx="${idx}" data-field="rate" value="${q.rate}" class="w-16 bg-white border border-slate-300 rounded-xl px-1.5 py-1.5 text-xs font-black text-center" />
              </div>
            </div>
            <input type="text" data-q-idx="${idx}" data-field="subtitle" value="${escapeHtml(q.subtitle || '')}" class="w-full bg-white border border-slate-300 rounded-xl px-2 py-1 text-[11px] text-slate-600" placeholder="Subtitle" />
            <div class="flex items-center justify-between pt-0.5">
              <button type="button" data-q-default="${idx}" class="px-2 py-1 rounded-lg text-[10px] font-black ${q.isDefault ? 'bg-amber-400 text-slate-950' : 'bg-slate-200 text-slate-700'}">
                ${q.isDefault ? '★ MOST USED DEFAULT' : 'SET AS DEFAULT'}
              </button>
              <button type="button" data-q-delete="${idx}" class="text-[11px] font-bold text-rose-600 active:text-rose-800">
                Delete
              </button>
            </div>
          `;
          qContainer.appendChild(item);
        });

        qContainer.querySelectorAll('input[data-q-idx]').forEach(inp => {
          inp.addEventListener('input', (e) => {
            const idx = Number(e.target.getAttribute('data-q-idx'));
            const field = e.target.getAttribute('data-field');
            if (field === 'rate') {
              appState.qualities[idx].rate = Math.max(0, Number(e.target.value) || 0);
            } else {
              appState.qualities[idx][field] = e.target.value;
            }
            saveState();
            renderCalculator();
          });
        });

        qContainer.querySelectorAll('button[data-q-default]').forEach(btn => {
          btn.addEventListener('click', () => {
            const idx = Number(btn.getAttribute('data-q-default'));
            appState.qualities.forEach((q, i) => { q.isDefault = (i === idx); });
            currentCalc.qualityId = appState.qualities[idx].id;
            saveState();
            renderSettings();
            renderCalculator();
            showToast('Default quality updated!');
          });
        });

        qContainer.querySelectorAll('button[data-q-delete]').forEach(btn => {
          btn.addEventListener('click', () => {
            if (appState.qualities.length <= 1) {
              showToast('Keep at least 1 quality.');
              return;
            }
            const idx = Number(btn.getAttribute('data-q-delete'));
            appState.qualities.splice(idx, 1);
            if (!appState.qualities.some(q => q.id === currentCalc.qualityId)) {
              currentCalc.qualityId = appState.qualities[0].id;
            }
            saveState();
            renderSettings();
            renderCalculator();
            showToast('Quality removed.');
          });
        });

        // 2. Labour list on mobile
        const lContainer = document.getElementById('settingsLabourList');
        lContainer.innerHTML = '';
        appState.labours.forEach((l, idx) => {
          const item = document.createElement('div');
          item.className = 'bg-slate-50 p-2.5 rounded-2xl border border-slate-200 space-y-2';
          item.innerHTML = `
            <div class="flex items-center justify-between gap-2">
              <input type="text" data-l-idx="${idx}" data-field="name" value="${escapeHtml(l.name)}" class="flex-1 bg-white border border-slate-300 rounded-xl px-2 py-1.5 text-xs font-bold" />
              <div class="flex items-center gap-1 shrink-0">
                <span class="text-xs font-bold text-slate-500">₹:</span>
                <input type="number" min="0" step="1" data-l-idx="${idx}" data-field="rate" value="${l.rate}" class="w-16 bg-white border border-slate-300 rounded-xl px-1.5 py-1.5 text-xs font-black text-center" />
              </div>
            </div>
            <input type="text" data-l-idx="${idx}" data-field="note" value="${escapeHtml(l.note || '')}" class="w-full bg-white border border-slate-300 rounded-xl px-2 py-1 text-[11px] text-slate-600" placeholder="Note" />
            <div class="flex items-center justify-between pt-0.5">
              <button type="button" data-l-default="${idx}" class="px-2 py-1 rounded-lg text-[10px] font-black ${l.isDefault ? 'bg-amber-400 text-slate-950' : 'bg-slate-200 text-slate-700'}">
                ${l.isDefault ? '★ DEFAULT LABOUR' : 'SET DEFAULT'}
              </button>
              <button type="button" data-l-delete="${idx}" class="text-[11px] font-bold text-rose-600 active:text-rose-800">
                Delete
              </button>
            </div>
          `;
          lContainer.appendChild(item);
        });

        lContainer.querySelectorAll('input[data-l-idx]').forEach(inp => {
          inp.addEventListener('input', (e) => {
            const idx = Number(e.target.getAttribute('data-l-idx'));
            const field = e.target.getAttribute('data-field');
            if (field === 'rate') {
              appState.labours[idx].rate = Math.max(0, Number(e.target.value) || 0);
            } else {
              appState.labours[idx][field] = e.target.value;
            }
            saveState();
            renderCalculator();
          });
        });

        lContainer.querySelectorAll('button[data-l-default]').forEach(btn => {
          btn.addEventListener('click', () => {
            const idx = Number(btn.getAttribute('data-l-default'));
            appState.labours.forEach((l, i) => { l.isDefault = (i === idx); });
            currentCalc.labourId = appState.labours[idx].id;
            saveState();
            renderSettings();
            renderCalculator();
            showToast('Default labour updated!');
          });
        });

        lContainer.querySelectorAll('button[data-l-delete]').forEach(btn => {
          btn.addEventListener('click', () => {
            if (appState.labours.length <= 1) {
              showToast('Keep at least 1 labour.');
              return;
            }
            const idx = Number(btn.getAttribute('data-l-delete'));
            appState.labours.splice(idx, 1);
            if (!appState.labours.some(l => l.id === currentCalc.labourId)) {
              currentCalc.labourId = appState.labours[0].id;
            }
            saveState();
            renderSettings();
            renderCalculator();
            showToast('Labour removed.');
          });
        });

        // 3. Misc Rules on mobile
        const mContainer = document.getElementById('settingsMiscList');
        mContainer.innerHTML = '';
        appState.miscRules.forEach((m, idx) => {
          const item = document.createElement('div');
          item.className = 'bg-slate-50 p-2.5 rounded-2xl border border-slate-200 space-y-2';
          item.innerHTML = `
            <div class="flex items-center justify-between gap-2">
              <div class="flex items-center gap-2 flex-1">
                <input type="checkbox" data-m-toggle="${idx}" ${m.active ? 'checked' : ''} class="w-4 h-4 accent-sky-600 rounded" />
                <input type="text" data-m-idx="${idx}" data-field="name" value="${escapeHtml(m.name)}" class="w-full bg-white border border-slate-300 rounded-xl px-2 py-1 text-xs font-bold" />
              </div>
              <button type="button" data-m-delete="${idx}" class="text-[11px] font-bold text-rose-600 px-1 py-1">Delete</button>
            </div>
            <div class="flex items-center gap-2">
              <select data-m-mode="${idx}" class="flex-1 bg-white border border-slate-300 rounded-xl px-1.5 py-1 text-xs font-semibold">
                <option value="per_ft" ${m.mode === 'per_ft' ? 'selected' : ''}>Per 1 ft</option>
                <option value="per_100ft" ${m.mode === 'per_100ft' ? 'selected' : ''}>Per 100 ft</option>
                <option value="custom_ft" ${m.mode === 'custom_ft' ? 'selected' : ''}>Custom ft</option>
                <option value="fixed" ${m.mode === 'fixed' ? 'selected' : ''}>Fixed ₹</option>
              </select>
              <div class="flex items-center gap-1 shrink-0">
                <span class="text-xs font-bold text-slate-500">₹:</span>
                <input type="number" min="0" step="1" data-m-idx="${idx}" data-field="rate" value="${m.rate}" class="w-16 bg-white border border-slate-300 rounded-xl px-1 py-1 text-xs font-black text-center" />
              </div>
              ${m.mode === 'custom_ft' ? `
                <div class="flex items-center gap-0.5 shrink-0">
                  <span class="text-[10px] text-slate-500">/</span>
                  <input type="number" min="1" step="1" data-m-idx="${idx}" data-field="unitFeet" value="${m.unitFeet || 154}" class="w-12 bg-white border border-slate-300 rounded-xl px-0.5 py-1 text-xs font-bold text-center" />
                  <span class="text-[10px] text-slate-500">ft</span>
                </div>
              ` : ''}
            </div>
          `;
          mContainer.appendChild(item);
        });

        mContainer.querySelectorAll('input[data-m-toggle]').forEach(chk => {
          chk.addEventListener('change', (e) => {
            const idx = Number(e.target.getAttribute('data-m-toggle'));
            appState.miscRules[idx].active = e.target.checked;
            saveState();
            renderCalculator();
          });
        });

        mContainer.querySelectorAll('select[data-m-mode]').forEach(sel => {
          sel.addEventListener('change', (e) => {
            const idx = Number(e.target.getAttribute('data-m-mode'));
            appState.miscRules[idx].mode = e.target.value;
            if (e.target.value === 'custom_ft' && !appState.miscRules[idx].unitFeet) {
              appState.miscRules[idx].unitFeet = 154;
            }
            saveState();
            renderSettings();
            renderCalculator();
          });
        });

        mContainer.querySelectorAll('input[data-m-idx]').forEach(inp => {
          inp.addEventListener('input', (e) => {
            const idx = Number(e.target.getAttribute('data-m-idx'));
            const field = e.target.getAttribute('data-field');
            if (field === 'rate') {
              appState.miscRules[idx].rate = Math.max(0, Number(e.target.value) || 0);
            } else if (field === 'unitFeet') {
              appState.miscRules[idx].unitFeet = Math.max(1, Number(e.target.value) || 1);
            } else {
              appState.miscRules[idx][field] = e.target.value;
            }
            saveState();
            renderCalculator();
          });
        });

        mContainer.querySelectorAll('button[data-m-delete]').forEach(btn => {
          btn.addEventListener('click', () => {
            const idx = Number(btn.getAttribute('data-m-delete'));
            appState.miscRules.splice(idx, 1);
            saveState();
            renderSettings();
            renderCalculator();
            showToast('Misc rule deleted.');
          });
        });
      }

      function renderHistory() {
        const list = appState.history || [];
        document.getElementById('savedQuotesCount').textContent = list.length;
        const hCount = document.getElementById('savedQuotesHeaderCount');
        if (hCount) hCount.textContent = list.length;

        const container = document.getElementById('historyListContainer');
        container.innerHTML = '';

        if (list.length === 0) {
          container.innerHTML = `
            <div class="bg-white rounded-2xl p-6 text-center border border-slate-200 text-slate-500 text-xs">
              No saved call quotes yet. Tap "Save Call Quote" while on a customer phone call.
            </div>
          `;
          return;
        }

        list.forEach((item, idx) => {
          const card = document.createElement('div');
          card.className = 'bg-white rounded-2xl p-3 shadow-sm border border-slate-200 flex items-center justify-between gap-2';
          card.innerHTML = `
            <div class="min-w-0 flex-1">
              <div class="flex items-center gap-1.5 flex-wrap">
                <span class="font-extrabold text-slate-900 text-xs truncate">${escapeHtml(item.customerName || 'Phone Caller')}</span>
                <span class="text-[10px] bg-sky-100 text-sky-800 font-bold px-1.5 py-0.2 rounded">${item.depth} ft</span>
              </div>
              <p class="text-[10px] text-slate-500 mt-0.5 truncate">
                ${escapeHtml(item.qualityName)} • ${escapeHtml(item.labourName)} • ${escapeHtml(item.timestamp)}
              </p>
            </div>
            <div class="flex items-center gap-1.5 shrink-0">
              <span class="text-sm font-black text-emerald-600">${formatINR(item.finalTotal)}</span>
              <button type="button" data-hist-load="${idx}" class="text-[11px] font-bold bg-slate-100 text-slate-800 px-2.5 py-1.5 rounded-xl">Load</button>
              <button type="button" data-hist-del="${idx}" class="text-[11px] font-bold text-rose-600 px-1.5 py-1.5">✕</button>
            </div>
          `;
          container.appendChild(card);
        });

        container.querySelectorAll('button[data-hist-load]').forEach(btn => {
          btn.addEventListener('click', () => {
            const item = appState.history[Number(btn.getAttribute('data-hist-load'))];
            if (!item) return;
            currentCalc.depth = item.depth;
            currentCalc.qualityId = item.qualityId;
            currentCalc.labourId = item.labourId;
            currentCalc.companyExtra = item.companyExtra || 0;
            currentCalc.customerName = item.customerName || '';
            currentCalc.discountMode = 'flat';
            currentCalc.discountValue = item.discountAmount || 0;

            document.getElementById('inputDepth').value = currentCalc.depth;
            document.getElementById('inputCompanyExtra').value = currentCalc.companyExtra;
            document.getElementById('inputCustomerName').value = currentCalc.customerName;
            document.getElementById('inputDiscountValue').value = currentCalc.discountValue;

            switchTab('calculator');
            renderCalculator();
            showToast('Quote loaded into Estimator!');
          });
        });

        container.querySelectorAll('button[data-hist-del]').forEach(btn => {
          btn.addEventListener('click', () => {
            const idx = Number(btn.getAttribute('data-hist-del'));
            appState.history.splice(idx, 1);
            saveState();
            renderHistory();
          });
        });
      }

      function escapeHtml(str) {
        return String(str || '')
          .replace(/&/g, '&amp;')
          .replace(/</g, '&lt;')
          .replace(/>/g, '&gt;')
          .replace(/"/g, '&quot;');
      }

      function switchTab(tabName) {
        ['calculator', 'settings', 'siri', 'history'].forEach(t => {
          const sec = document.getElementById('tab-' + t);
          if (sec) sec.classList.toggle('hidden', t !== tabName);
        });
        document.querySelectorAll('.nav-tab').forEach(btn => {
          const active = btn.getAttribute('data-tab') === tabName;
          if (active) {
            btn.className = 'nav-tab flex-1 flex flex-col items-center justify-center py-1 text-sky-400 font-bold transition';
          } else {
            btn.className = 'nav-tab flex-1 flex flex-col items-center justify-center py-1 text-slate-400 hover:text-white font-medium transition';
          }
        });
        window.scrollTo({ top: 0, behavior: 'smooth' });
      }

      function speakEstimateAloud() {
        const est = calculateEstimate();
        const text = `For a ${est.depth} feet borewell, the final price estimate is ${Math.round(est.finalTotal)} rupees.`;
        if ('speechSynthesis' in window) {
          try {
            window.speechSynthesis.cancel();
            const utter = new SpeechSynthesisUtterance(text);
            utter.lang = 'en-IN';
            window.speechSynthesis.speak(utter);
          } catch (e) {
            console.warn(e);
          }
        }
        showToast(text);
      }

      function parseVoiceOrSiriCommand(phrase, shouldSpeak) {
        const lower = String(phrase || '').toLowerCase();
        const depthMatch = lower.match(/(\d+)\s*(?:ft|feet|foot)/) || lower.match(/\b(\d{2,4})\b/);
        if (depthMatch) {
          currentCalc.depth = Number(depthMatch[1]);
          document.getElementById('inputDepth').value = currentCalc.depth;
        }

        for (const q of appState.qualities) {
          const tokens = (q.name + ' ' + (q.subtitle || '')).toLowerCase().split(/[^a-z0-9]+/).filter(Boolean);
          if (tokens.some(t => t.length > 2 && lower.includes(t))) {
            currentCalc.qualityId = q.id;
            break;
          }
        }

        for (const l of appState.labours) {
          const tokens = (l.name + ' ' + (l.note || '')).toLowerCase().split(/[^a-z0-9]+/).filter(Boolean);
          if (tokens.some(t => t.length > 3 && lower.includes(t))) {
            currentCalc.labourId = l.id;
            break;
          }
        }

        const extraMatch = lower.match(/(?:extra|company|margin|add)\s*(?:of\s*)?(?:rs\.?|rupees|₹)?\s*(\d+)/);
        if (extraMatch) {
          currentCalc.companyExtra = Number(extraMatch[1]);
          document.getElementById('inputCompanyExtra').value = currentCalc.companyExtra;
        }

        const discMatch = lower.match(/(?:discount|less|off)\s*(?:of\s*)?(?:rs\.?|rupees|₹)?\s*(\d+)/);
        if (discMatch) {
          currentCalc.discountMode = 'flat';
          currentCalc.discountValue = Number(discMatch[1]);
          document.getElementById('inputDiscountValue').value = currentCalc.discountValue;
        }

        renderCalculator();
        switchTab('calculator');
        if (shouldSpeak) {
          speakEstimateAloud();
        } else {
          showToast('Voice applied: ' + currentCalc.depth + ' ft');
        }
      }

      function shareWhatsAppQuote() {
        const est = calculateEstimate();
        const lines = [
          `*${appState.companyName}*`,
          `Borewell Instant Estimate:`,
          currentCalc.customerName ? `Customer: ${currentCalc.customerName}` : '',
          `• Depth: *${est.depth} ft*`,
          `• Pipe Quality: ${est.quality ? est.quality.name : ''} (${formatINR(est.pipeCost)})`,
          `• Labour: ${est.labour ? est.labour.name : ''} (${formatINR(est.labourCost)})`,
          `• Misc Costs: ${formatINR(est.miscTotal)}`,
          est.companyExtra > 0 ? `• Company Extra: ${formatINR(est.companyExtra)}` : '',
          est.discountAmount > 0 ? `• Discount: -${formatINR(est.discountAmount)}` : '',
          `*Total Price: ${formatINR(est.finalTotal)}*`
        ].filter(Boolean).join('\n');

        if (navigator.clipboard && navigator.clipboard.writeText) {
          navigator.clipboard.writeText(lines).then(() => {
            showToast('Quote copied for WhatsApp!');
          }).catch(() => fallbackCopy(lines));
        } else {
          fallbackCopy(lines);
        }

        const waUrl = 'https://wa.me/?text=' + encodeURIComponent(lines);
        try {
          window.open(waUrl, '_blank');
        } catch (e) {}
      }

      function fallbackCopy(text) {
        const ta = document.createElement('textarea');
        ta.value = text;
        document.body.appendChild(ta);
        ta.select();
        try { document.execCommand('copy'); } catch (e) {}
        document.body.removeChild(ta);
        showToast('Quote copied to clipboard!');
      }

      function applyUrlParamsForSiri() {
        const params = new URLSearchParams(window.location.search);
        if (!params.has('depth') && !params.has('q')) return;

        if (params.has('q')) {
          parseVoiceOrSiriCommand(params.get('q'), params.get('speak') === '1');
          return;
        }

        if (params.has('depth')) {
          currentCalc.depth = Math.max(1, Number(params.get('depth')) || 550);
          document.getElementById('inputDepth').value = currentCalc.depth;
        }
        if (params.has('quality')) {
          const qParam = params.get('quality').toLowerCase();
          const foundQ = appState.qualities.find(q =>
            q.name.toLowerCase().includes(qParam) || (q.subtitle || '').toLowerCase().includes(qParam)
          );
          if (foundQ) currentCalc.qualityId = foundQ.id;
        }
        if (params.has('labour')) {
          const lParam = params.get('labour').toLowerCase();
          const foundL = appState.labours.find(l => l.name.toLowerCase().includes(lParam));
          if (foundL) currentCalc.labourId = foundL.id;
        }
        if (params.has('extra')) {
          currentCalc.companyExtra = Math.max(0, Number(params.get('extra')) || 0);
          document.getElementById('inputCompanyExtra').value = currentCalc.companyExtra;
        }
        if (params.has('discount')) {
          currentCalc.discountMode = 'flat';
          currentCalc.discountValue = Math.max(0, Number(params.get('discount')) || 0);
          document.getElementById('inputDiscountValue').value = currentCalc.discountValue;
        }
        renderCalculator();
        if (params.get('speak') === '1') {
          setTimeout(speakEstimateAloud, 400);
        }
      }

      // Initialize
      window.addEventListener('DOMContentLoaded', () => {
        loadState();

        document.getElementById('inputDepth').value = currentCalc.depth;
        document.getElementById('inputCompanyExtra').value = currentCalc.companyExtra;

        renderCalculator();
        renderSettings();
        renderHistory();
        applyUrlParamsForSiri();

        // Bottom Nav tabs
        document.querySelectorAll('.nav-tab').forEach(btn => {
          btn.addEventListener('click', () => {
            switchTab(btn.getAttribute('data-tab'));
          });
        });

        document.getElementById('btnJumpPipeSettings').addEventListener('click', () => switchTab('settings'));
        document.getElementById('btnJumpLabourSettings').addEventListener('click', () => switchTab('settings'));

        // Depth Steppers (-50 / +50)
        document.getElementById('btnDepthMinus50').addEventListener('click', () => {
          currentCalc.depth = Math.max(10, (Number(currentCalc.depth) || 550) - 50);
          document.getElementById('inputDepth').value = currentCalc.depth;
          renderCalculator();
        });
        document.getElementById('btnDepthPlus50').addEventListener('click', () => {
          currentCalc.depth = Math.max(10, (Number(currentCalc.depth) || 550) + 50);
          document.getElementById('inputDepth').value = currentCalc.depth;
          renderCalculator();
        });

        document.getElementById('inputDepth').addEventListener('input', (e) => {
          currentCalc.depth = Math.max(0, Number(e.target.value) || 0);
          renderCalculator();
        });

        document.querySelectorAll('.depth-chip').forEach(btn => {
          btn.addEventListener('click', () => {
            currentCalc.depth = Number(btn.getAttribute('data-depth'));
            document.getElementById('inputDepth').value = currentCalc.depth;
            renderCalculator();
          });
        });

        // Company Extra & Customer Name
        document.getElementById('inputCompanyExtra').addEventListener('input', (e) => {
          currentCalc.companyExtra = Math.max(0, Number(e.target.value) || 0);
          renderCalculator();
        });
        document.getElementById('inputCustomerName').addEventListener('input', (e) => {
          currentCalc.customerName = e.target.value;
        });

        // Discount Mode Toggle
        const btnFlat = document.getElementById('btnDiscModeFlat');
        const btnPct = document.getElementById('btnDiscModePct');
        btnFlat.addEventListener('click', () => {
          currentCalc.discountMode = 'flat';
          document.getElementById('discPrefix').textContent = '₹';
          btnFlat.className = 'px-2 py-0.5 text-[10px] font-black rounded-md bg-amber-500 text-slate-950 transition';
          btnPct.className = 'px-2 py-0.5 text-[10px] font-bold rounded-md text-slate-600 transition';
          renderCalculator();
        });
        btnPct.addEventListener('click', () => {
          currentCalc.discountMode = 'pct';
          document.getElementById('discPrefix').textContent = '%';
          btnPct.className = 'px-2 py-0.5 text-[10px] font-black rounded-md bg-amber-500 text-slate-950 transition';
          btnFlat.className = 'px-2 py-0.5 text-[10px] font-bold rounded-md text-slate-600 transition';
          renderCalculator();
        });

        document.getElementById('inputDiscountValue').addEventListener('input', (e) => {
          currentCalc.discountValue = Math.max(0, Number(e.target.value) || 0);
          renderCalculator();
        });

        document.querySelectorAll('[data-disc-chip]').forEach(btn => {
          btn.addEventListener('click', () => {
            currentCalc.discountMode = 'flat';
            currentCalc.discountValue = Number(btn.getAttribute('data-disc-chip'));
            document.getElementById('inputDiscountValue').value = currentCalc.discountValue;
            btnFlat.click();
          });
        });

        document.querySelectorAll('[data-disc-pct-chip]').forEach(btn => {
          btn.addEventListener('click', () => {
            currentCalc.discountMode = 'pct';
            currentCalc.discountValue = Number(btn.getAttribute('data-disc-pct-chip'));
            document.getElementById('inputDiscountValue').value = currentCalc.discountValue;
            btnPct.click();
          });
        });

        document.getElementById('btnRoundPrice').addEventListener('click', () => {
          const est = calculateEstimate();
          const remainder = est.grossTotal % 500;
          const roundedDiscount = remainder > 0 ? remainder : 500;
          currentCalc.discountMode = 'flat';
          currentCalc.discountValue = Math.round(roundedDiscount);
          document.getElementById('inputDiscountValue').value = currentCalc.discountValue;
          btnFlat.click();
          showToast('Rounded to nearest ₹500!');
        });

        document.getElementById('btnClearDiscount').addEventListener('click', () => {
          currentCalc.discountValue = 0;
          document.getElementById('inputDiscountValue').value = 0;
          renderCalculator();
        });

        // Toggle Breakdown Drawer
        const breakdownToggle = document.getElementById('btnToggleBreakdown');
        const breakdownCont = document.getElementById('breakdownContainer');
        const breakdownLabel = document.getElementById('breakdownToggleLabel');
        const breakdownIcon = document.getElementById('breakdownToggleIcon');
        breakdownToggle.addEventListener('click', () => {
          const isHidden = breakdownCont.classList.contains('hidden');
          breakdownCont.classList.toggle('hidden', !isHidden);
          breakdownLabel.textContent = isHidden ? 'Hide Details' : 'Show Details';
          breakdownIcon.style.transform = isHidden ? 'rotate(180deg)' : 'rotate(0deg)';
        });

        // WhatsApp & Quote Action buttons
        document.getElementById('btnQuickWhatsAppTop').addEventListener('click', shareWhatsAppQuote);
        document.getElementById('btnCopyQuote').addEventListener('click', shareWhatsAppQuote);
        document.getElementById('btnSpeakEstimate').addEventListener('click', speakEstimateAloud);

        document.getElementById('btnSaveQuote').addEventListener('click', () => {
          const est = calculateEstimate();
          const now = new Date();
          appState.history.unshift({
            customerName: currentCalc.customerName || 'Caller',
            depth: est.depth,
            qualityId: currentCalc.qualityId,
            qualityName: est.quality ? est.quality.name : 'Pipe',
            labourId: currentCalc.labourId,
            labourName: est.labour ? est.labour.name : 'Labour',
            companyExtra: est.companyExtra,
            discountAmount: est.discountAmount,
            finalTotal: est.finalTotal,
            timestamp: now.toLocaleTimeString([], { hour: '2-digit', minute: '2-digit' })
          });
          saveState();
          renderHistory();
          showToast('Saved to Call Quotes!');
        });

        // Settings CRUD Handlers
        document.getElementById('btnAddQuality').addEventListener('click', () => {
          const name = document.getElementById('newQualityName').value.trim();
          const subtitle = document.getElementById('newQualitySubtitle').value.trim();
          const rate = Number(document.getElementById('newQualityRate').value);
          if (!name || isNaN(rate) || rate < 0) {
            showToast('Enter valid quality name and ₹/ft rate.');
            return;
          }
          appState.qualities.push({ id: 'q_' + Date.now(), name, subtitle, rate, isDefault: false });
          document.getElementById('newQualityName').value = '';
          document.getElementById('newQualitySubtitle').value = '';
          document.getElementById('newQualityRate').value = '';
          saveState();
          renderSettings();
          renderCalculator();
          showToast('Added: ' + name);
        });

        document.getElementById('btnAddLabour').addEventListener('click', () => {
          const name = document.getElementById('newLabourName').value.trim();
          const note = document.getElementById('newLabourNote').value.trim();
          const rate = Number(document.getElementById('newLabourRate').value);
          if (!name || isNaN(rate) || rate < 0) {
            showToast('Enter valid labour name and ₹/ft rate.');
            return;
          }
          appState.labours.push({ id: 'l_' + Date.now(), name, note, rate, isDefault: false });
          document.getElementById('newLabourName').value = '';
          document.getElementById('newLabourNote').value = '';
          document.getElementById('newLabourRate').value = '';
          saveState();
          renderSettings();
          renderCalculator();
          showToast('Added: ' + name);
        });

        document.getElementById('newMiscMode').addEventListener('change', (e) => {
          const wrap = document.getElementById('newMiscCustomFtWrap');
          wrap.classList.toggle('hidden', e.target.value !== 'custom_ft');
        });

        document.getElementById('btnAddMisc').addEventListener('click', () => {
          const name = document.getElementById('newMiscName').value.trim();
          const mode = document.getElementById('newMiscMode').value;
          const rate = Number(document.getElementById('newMiscRate').value);
          const unitFeet = Math.max(1, Number(document.getElementById('newMiscUnitFeet').value) || 154);
          if (!name || isNaN(rate) || rate < 0) {
            showToast('Enter valid misc name and ₹ amount.');
            return;
          }
          appState.miscRules.push({
            id: 'm_' + Date.now(),
            name,
            mode,
            rate,
            unitFeet,
            active: true
          });
          document.getElementById('newMiscName').value = '';
          document.getElementById('newMiscRate').value = '';
          saveState();
          renderSettings();
          renderCalculator();
          showToast('Added: ' + name);
        });

        document.getElementById('btnSaveBusinessSettings').addEventListener('click', () => {
          appState.companyName = document.getElementById('settingCompanyName').value.trim() || 'Borewell QuickQuote';
          appState.defaultDepth = Math.max(1, Number(document.getElementById('settingDefaultDepth').value) || 550);
          appState.defaultExtra = Math.max(0, Number(document.getElementById('settingDefaultExtra').value) || 0);
          saveState();
          renderCalculator();
          showToast('Saved business defaults!');
        });

        document.getElementById('btnLoadPromptExample').addEventListener('click', () => {
          appState.qualities = [
            { id: 'q_good', name: 'Moderate / Good', subtitle: 'Budget Friendly • Most Used', rate: 10, isDefault: true },
            { id: 'q_better', name: 'Better Quality', subtitle: 'Medium Casing Pipe', rate: 16, isDefault: false },
            { id: 'q_best', name: 'Best Quality', subtitle: 'Heavy ISI Pipe', rate: 24, isDefault: false }
          ];
          appState.labours = [
            { id: 'l_cheap', name: 'Cheap Labour', note: 'Standard Drilling Crew', rate: 20, isDefault: true },
            { id: 'l_exp', name: 'Expensive Labour', note: 'Fast Heavy Rig Crew', rate: 32, isDefault: false }
          ];
          appState.miscRules = [
            { id: 'm_154', name: 'Custom Depth Misc', mode: 'custom_ft', rate: 308, unitFeet: 154, active: true },
            { id: 'm_100', name: 'Rig Maint. (Per 100ft)', mode: 'per_100ft', rate: 100, unitFeet: 100, active: true }
          ];
          currentCalc.depth = 550;
          currentCalc.qualityId = 'q_good';
          currentCalc.labourId = 'l_cheap';
          document.getElementById('inputDepth').value = 550;
          saveState();
          renderSettings();
          renderCalculator();
          switchTab('calculator');
          showToast('Loaded ₹10 Pipe + ₹20 Labour Demo!');
        });

        document.getElementById('btnResetDefaults').addEventListener('click', () => {
          appState = getDefaultState();
          saveState();
          loadState();
          renderSettings();
          renderCalculator();
          renderHistory();
          showToast('Reset to defaults.');
        });

        document.getElementById('btnClearHistory').addEventListener('click', () => {
          appState.history = [];
          saveState();
          renderHistory();
          showToast('Cleared history.');
        });

        // Voice Handlers
        const voiceBanner = document.getElementById('voiceStatusBanner');
        document.getElementById('btnVoiceQuick').addEventListener('click', () => {
          voiceBanner.classList.remove('hidden');
          const SpeechRec = window.SpeechRecognition || window.webkitSpeechRecognition;
          if (SpeechRec) {
            try {
              const rec = new SpeechRec();
              rec.lang = 'en-IN';
              rec.interimResults = false;
              document.getElementById('voiceTranscriptText').textContent = 'Listening... Speak depth & quality';
              rec.onresult = (ev) => {
                const transcript = ev.results[0][0].transcript;
                document.getElementById('voiceTranscriptText').textContent = 'Heard: "' + transcript + '"';
                parseVoiceOrSiriCommand(transcript, true);
              };
              rec.onerror = () => {
                document.getElementById('voiceTranscriptText').textContent = 'Mic blocked in sandbox — tap 550ft Demo!';
              };
              rec.start();
            } catch (e) {
              document.getElementById('voiceTranscriptText').textContent = 'Tap 550ft Demo button!';
            }
          } else {
            document.getElementById('voiceTranscriptText').textContent = 'Tap 550ft Demo button!';
          }
        });

        document.getElementById('btnSimulateVoice550').addEventListener('click', () => {
          parseVoiceOrSiriCommand('550 feet moderate quality cheap labour', true);
          voiceBanner.classList.add('hidden');
        });

        document.getElementById('btnCloseVoiceBanner').addEventListener('click', () => {
          voiceBanner.classList.add('hidden');
        });

        document.getElementById('btnRunVoiceCommand').addEventListener('click', () => {
          const phrase = document.getElementById('voiceCommandInput').value;
          parseVoiceOrSiriCommand(phrase, true);
        });

        document.querySelectorAll('.sample-phrase').forEach(btn => {
          btn.addEventListener('click', () => {
            const p = btn.getAttribute('data-phrase');
            document.getElementById('voiceCommandInput').value = p;
            parseVoiceOrSiriCommand(p, true);
          });
        });

        document.getElementById('btnCopySiriUrl').addEventListener('click', () => {
          const url = window.location.origin + window.location.pathname + document.getElementById('siriUrlPreview').textContent;
          fallbackCopy(url);
        });
      });
    })();
  </script>
</body>
</html>