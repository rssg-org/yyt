<template>
  <div class="header-wrapper fixed-header">
    <button
      type="button"
      class="home-button"
      @click="$router.push('/')"
      aria-label="トップページへ戻る"
    >
      <svg viewBox="0 0 90 20" preserveAspectRatio="xMidYMid meet" focusable="false" class="logo-icon">
        <g viewBox="0 0 90 20" preserveAspectRatio="xMidYMid meet">
          <g>
            <path d="M27.9727 3.12324C27.6435 1.89323 26.6768 0.926623 25.4468 0.597366C23.2197 2.24288e-07 14.285 0 14.285 0C14.285 0 5.35042 2.24288e-07 3.12323 0.597366C1.89323 0.926623 0.926623 1.89323 0.597366 3.12324C2.24288e-07 5.35042 0 10 0 10C0 10 2.24288e-07 14.6496 0.597366 16.8768C0.926623 18.1068 1.89323 19.0734 3.12323 19.4026C5.35042 20 14.285 20 14.285 20C14.285 20 23.2197 20 25.4468 19.4026C26.6768 19.0734 27.6435 18.1068 27.9727 16.8768C28.5701 14.6496 28.5701 10 28.5701 10C28.5701 10 28.5677 5.35042 27.9727 3.12324Z" fill="#FF0000"></path>
            <path d="M11.4253 14.2854L18.8477 10.0004L11.4253 5.71533V14.2854Z" fill="white"></path>
          </g>
          <g>
            <path d="M34.6024 13.0036L31.3945 1.41846H34.1932L35.3174 6.6701C35.6043 7.96361 35.8136 9.06662 35.95 9.97913H36.0323C36.1264 9.32532 36.3381 8.22937 36.665 6.68892L37.8291 1.41846H40.6278L37.3799 13.0036V18.561H34.6001V13.0036H34.6024Z" fill="currentColor"></path>
            <path d="M41.4697 18.1937C40.9053 17.8127 40.5031 17.22 40.2632 16.4157C40.0257 15.6114 39.9058 14.5437 39.9058 13.2078V11.3898C39.9058 10.0422 40.0422 8.95805 40.315 8.14196C40.5878 7.32588 41.0135 6.72851 41.592 6.35457C42.1706 5.98063 42.9302 5.79248 43.871 5.79248C44.7976 5.79248 45.5384 5.98298 46.0981 6.36398C46.6555 6.74497 47.0672 7.34234 47.3331 8.15137C47.599 8.96275 47.7319 10.0422 47.7319 11.3898V13.2078C47.7319 14.5437 47.6155 15.6161 47.3803 16.4251C47.1452 17.2365 46.7478 17.8292 46.1881 18.2031C45.6285 18.5771 44.8753 18.7652 43.9264 18.7652C42.9302 18.7675 42.0365 18.5747 41.4697 18.1937ZM44.6353 16.2323C44.7905 15.8231 44.8705 15.1575 44.8705 14.2309V10.3292C44.8705 9.43077 44.7929 8.77225 44.6353 8.35833C44.4777 7.94206 44.2026 7.7351 43.8074 7.7351C43.4265 7.7351 43.156 7.94206 43.0008 8.35833C42.8432 8.77461 42.7656 9.43077 42.7656 10.3292V14.2309C42.7656 15.1575 42.8408 15.8254 42.9914 16.2323C43.1419 16.6415 43.4123 16.8461 43.8074 16.8461C44.2026 16.8461 44.4777 16.6415 44.6353 16.2323Z" fill="currentColor"></path>
            <path d="M56.8154 18.5634H54.6094L54.3648 17.03H54.3037C53.7039 18.1871 52.8055 18.7656 51.6061 18.7656C50.7759 18.7656 50.1621 18.4928 49.767 17.9496C49.3719 17.4039 49.1743 16.5526 49.1743 15.3955V6.03751H51.9942V15.2308C51.9942 15.7906 52.0553 16.188 52.1776 16.4256C52.2999 16.6631 52.5045 16.783 52.7914 16.783C53.036 16.783 53.2712 16.7078 53.497 16.5573C53.7228 16.4067 53.8874 16.2162 53.9979 15.9858V6.03516H56.8154V18.5634Z" fill="currentColor"></path>
            <path d="M64.4755 3.68758H61.6768V18.5629H58.9181V3.68758H56.1194V1.42041H64.4755V3.68758Z" fill="currentColor"></path>
            <path d="M71.2768 18.5634H69.0708L68.8262 17.03H68.7651C68.1654 18.1871 67.267 18.7656 66.0675 18.7656C65.2373 18.7656 64.6235 18.4928 64.2284 17.9496C63.8333 17.4039 63.6357 16.5526 63.6357 15.3955V6.03751H66.4556V15.2308C66.4556 15.7906 66.5167 16.188 66.639 16.4256C66.7613 16.6631 66.9659 16.783 67.2529 16.783C67.4974 16.783 67.7326 16.7078 67.9584 16.5573C68.1842 16.4067 68.3488 16.2162 68.4593 15.9858V6.03516H71.2768V18.5634Z" fill="currentColor"></path>
            <path d="M80.609 8.0387C80.4373 7.24849 80.1621 6.67699 79.7812 6.32186C79.4002 5.96674 78.8757 5.79035 78.2078 5.79035C77.6904 5.79035 77.2059 5.93616 76.7567 6.23014C76.3075 6.52412 75.9594 6.90747 75.7148 7.38489H75.6937V0.785645H72.9773V18.5608H75.3056L75.5925 17.3755H75.6537C75.8724 17.7988 76.1993 18.1304 76.6344 18.3774C77.0695 18.622 77.554 18.7443 78.0855 18.7443C79.038 18.7443 79.7412 18.3045 80.1904 17.4272C80.6396 16.5476 80.8653 15.1765 80.8653 13.3092V11.3266C80.8653 9.92722 80.7783 8.82892 80.609 8.0387ZM78.0243 13.1492C78.0243 14.0617 77.9867 14.7767 77.9114 15.2941C77.8362 15.8115 77.7115 16.1808 77.5328 16.3971C77.3564 16.6158 77.1165 16.724 76.8178 16.724C76.585 16.724 76.371 16.6699 76.1734 16.5594C75.9759 16.4512 75.816 16.2866 75.6937 16.0702V8.96062C75.7877 8.6196 75.9524 8.34209 76.1852 8.12337C76.4157 7.90465 76.6697 7.79646 76.9401 7.79646C77.2271 7.79646 77.4481 7.90935 77.6034 8.13278C77.7588 8.35855 77.8691 8.73485 77.9303 9.26636C77.9914 9.79787 78.022 10.5528 78.022 11.5335V13.1492H78.0243Z" fill="currentColor"></path>
            <path d="M84.8657 13.8712C84.8657 14.6755 84.8892 15.2776 84.9363 15.6798C84.9833 16.0819 85.0821 16.3736 85.2326 16.5594C85.3831 16.7428 85.6136 16.8345 85.9264 16.8345C86.3474 16.8345 86.639 16.6699 86.7942 16.343C86.9518 16.0161 87.0365 15.4705 87.0506 14.7085L89.4824 14.8519C89.4965 14.9601 89.5035 15.1106 89.5035 15.3011C89.5035 16.4582 89.186 17.3237 88.5534 17.8952C87.9208 18.4667 87.0247 18.7536 85.8676 18.7536C84.4777 18.7536 83.504 18.3185 82.9466 17.446C82.3869 16.5735 82.1094 15.2259 82.1094 13.4008V11.2136C82.1094 9.33452 82.3987 7.96105 82.9772 7.09558C83.5558 6.2301 84.5459 5.79736 85.9499 5.79736C86.9165 5.79736 87.6597 5.97375 88.1771 6.32888C88.6945 6.684 89.059 7.23433 89.2707 7.98457C89.4824 8.7348 89.5882 9.76961 89.5882 11.0913V13.2362H84.8657V13.8712ZM85.2232 7.96811C85.0797 8.14449 84.9857 8.43377 84.9363 8.83593C84.8892 9.2381 84.8657 9.84722 84.8657 10.6657V11.5641H86.9283V10.6657C86.9283 9.86133 86.9001 9.25221 86.846 8.83593C86.7919 8.41966 86.6931 8.12803 86.5496 7.95635C86.4062 7.78702 86.1851 7.7 85.8864 7.7C85.5854 7.70235 85.3643 7.79172 85.2232 7.96811Z" fill="currentColor"></path>
          </g>
        </g>
      </svg>
    </button>

    <form @submit.prevent="onSubmit" class="header-search" ref="searchFormRef">
      <input
        type="text"
        v-model="query"
        @input="onInput"
        @keydown.down.prevent="moveSelection(1)"
        @keydown.up.prevent="moveSelection(-1)"
        @keydown.enter.prevent="onEnter"
        placeholder="キーワードを入力..."
        autocomplete="off"
        class="search-input"
        aria-label="Search"
      />
      <!-- 🔍検索ボタンの前に追加 -->
<button
  v-if="query"
  type="button"
  class="clear-button"
  @click="clearQuery"
  aria-label="入力をクリア"
>
  ×
</button>

      <button type="submit" class="search-button" aria-label="検索">
        <img
          :src="searchiconIcon"
          alt="🔍"
          style="width: 20px; height: 20px"
        />
      </button>

      <ul v-if="suggestions.length" class="suggestions-list" role="listbox">
        <li
          v-for="(item, index) in suggestions"
          :key="index"
          :class="{ selected: index === selectedIndex }"
          @mousedown.prevent="onSuggestionClick(index)"
          role="option"
          :aria-selected="index === selectedIndex"
        >
          {{ item }}
        </li>
      </ul>
    </form>

    <!-- 右側に設定ボタンとモーダル -->
    <div class="header-settings">
      <button class="settings-button" type="button" @click="toggleSettings" aria-label="設定を開く">
        <img :src="settingIcon" alt="設定アイコン" style="width: 30px; height: 30px;" />
      </button>

      <div v-if="settingsOpen" class="settings-modal" role="dialog" aria-modal="true">
        <h3>API エンドポイント設定</h3>

        <div class="mode-group">
          <label><input type="radio" v-model="mode" value="existing" /> 既存 API のみを使用</label>
          <label><input type="radio" v-model="mode" value="custom" /> カスタムのみを使用</label>
          <label><input type="radio" v-model="mode" value="both" /> 両方をランダムに使用</label>
        </div>

        <!-- デフォルト再生方式の追加 -->
        <div class="playback-default">
          <h4>デフォルト再生方式</h4>
          <label><input type="radio" v-model="defaultPlaybackMode" value="1" /> 通常</label>
          <label><input type="radio" v-model="defaultPlaybackMode" value="2" /> タイプ２</label>
        </div>

        <div class="custom-list">
          <h4>カスタムエンドポイント</h4>
          <ul>
            <li v-for="(url, i) in customEndpoints" :key="i">
              <span class="endpoint-text">{{ url }}</span>
              <button type="button" class="remove-btn" @click="removeEndpoint(i)" aria-label="削除">削除</button>
            </li>
            <li v-if="customEndpoints.length === 0">
              <CustomEndpointsHelp />
            </li>
          </ul>

          <div class="add-row">
            <input type="text" v-model="newEndpoint" placeholder="https://example.com/endpoint" />
            <button type="button" @click="addEndpoint">追加</button>
          </div>
        </div>

        <div class="settings-actions">
          <button type="button" @click="closeSettings">閉じる</button>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
import settingIcon from '/Image/setting.txt?raw'
import searchiconIcon from '/Image/searchicon.txt?raw'
import CustomEndpointsHelp from "./CustomEndpointsHelp.vue";

import { ref, onMounted, onBeforeUnmount, watch } from "vue";
import { useRouter } from "vue-router";
import { apiurl, STORAGE_KEY, MODE_KEY } from "../api.js";
import {
  getEffectiveApiUrl,
  loadCustomEndpoints as rmLoadCustomEndpoints,
  saveCustomEndpoints as rmSaveCustomEndpoints,
  loadMode as rmLoadMode,
  saveMode as rmSaveMode,
} from "@/services/requestManager";

const router = useRouter();
// 変更: 詳細イベントを追加で定義
const emit = defineEmits(["search", "searchMeta"]);

const query = ref("");
const suggestions = ref([]);
const selectedIndex = ref(-1);
let fetchController = null;

const searchFormRef = ref(null);

const onClickOutside = (event) => {
  if (searchFormRef.value && !searchFormRef.value.contains(event.target)) {
    suggestions.value = [];
    selectedIndex.value = -1;
  }
};

onMounted(() => {
  document.addEventListener("click", onClickOutside);
  router.push('/');
  // load custom endpoints from requestManager (centralized)
  try {
    customEndpoints.value = rmLoadCustomEndpoints() || [];
  } catch (e) {
    customEndpoints.value = [];
  }
  // load saved mode
  try {
    const m = rmLoadMode();
    if (m) mode.value = m;
  } catch (e) {}
  // load default playback mode from cookie/localStorage
  try {
    const m = (document.cookie.match(new RegExp("(^| )StreamType=([^;]+)")) || [])[2];
    if (m) {
      defaultPlaybackMode.value = decodeURIComponent(m);
    } else {
      defaultPlaybackMode.value = localStorage.getItem("defaultPlaybackMode") || "1";
      // ensure cookie is set to keep compatibility with VideoPlayer
      saveDefaultPlayback();
    }
  } catch (e) {
    defaultPlaybackMode.value = localStorage.getItem("defaultPlaybackMode") || "1";
  }
});

onBeforeUnmount(() => {
  document.removeEventListener("click", onClickOutside);
});

const fetchSuggestions = async (keyword) => {
  if (!keyword) {
    suggestions.value = [];
    selectedIndex.value = -1;
    return;
  }
  if (fetchController) fetchController.abort();
  fetchController = new AbortController();

  try {
    const res = await fetch(
      `https://www.google.com/complete/search?client=youtube&hl=ja&ds=yt&q=${encodeURIComponent(keyword)}`,
      { signal: fetchController.signal }
    );
    if (!res.ok) throw new Error("Network error");
    const data = await res.json();
    suggestions.value = data;
    selectedIndex.value = -1;
  } catch (e) {
    if (e.name !== "AbortError") {
      suggestions.value = [];
      selectedIndex.value = -1;
      console.error(e);
    }
  }
};

const onInput = () => {
  fetchSuggestions(query.value.trim());
};

const moveSelection = (delta) => {
  if (suggestions.value.length === 0) return;
  selectedIndex.value += delta;
  if (selectedIndex.value < 0) selectedIndex.value = suggestions.value.length - 1;
  if (selectedIndex.value >= suggestions.value.length) selectedIndex.value = 0;
  query.value = suggestions.value[selectedIndex.value];
};

const onEnter = () => {
  if (selectedIndex.value >= 0) {
    query.value = suggestions.value[selectedIndex.value];
  }
  submitSearch();
};

const onSuggestionClick = (index) => {
  query.value = suggestions.value[index];
  submitSearch();
};

// --- ここから設定・カスタムエンドポイント管理 ---
const settingsOpen = ref(false);
const customEndpoints = ref([]);
const newEndpoint = ref("");
const mode = ref("existing"); // existing | custom | both

// デフォルト再生方式: '1' = 通常, '2' = タイプ2
const defaultPlaybackMode = ref("1");

function saveDefaultPlayback() {
  try {
    // cookie に保存（VideoPlayer が参照するため）
    const seconds = 60 * 60 * 24 * 365 * 10; // 10年
    const expires = new Date(Date.now() + seconds * 1000).toUTCString();
    document.cookie = `StreamType=${encodeURIComponent(
      defaultPlaybackMode.value
    )}; expires=${expires}; path=/`;
    // ローカルにも保存して UI の初期化に使う
    localStorage.setItem("defaultPlaybackMode", defaultPlaybackMode.value);
  } catch (e) {
    console.error("saveDefaultPlayback error", e);
  }
}

// defaultPlaybackMode が変わったら保存
watch(defaultPlaybackMode, () => {
  saveDefaultPlayback();
});

const STORAGE_KEY_LOCAL = STORAGE_KEY; // from api.js (kept for compatibility)

function loadCustomEndpoints() {
  // load via requestManager wrapper (keeps single source of truth)
  try {
    customEndpoints.value = rmLoadCustomEndpoints() || [];
  } catch {
    customEndpoints.value = [];
  }
}

function saveCustomEndpoints() {
  try {
    rmSaveCustomEndpoints(customEndpoints.value || []);
  } catch (e) {
    console.error("saveCustomEndpoints error", e);
  }
}

function isValidUrl(url) {
  try {
    const u = new URL(url);
    return u.protocol === "http:" || u.protocol === "https:";
  } catch {
    return false;
  }
}

function addEndpoint() {
  const v = newEndpoint.value.trim();
  if (!v) return;
  if (!isValidUrl(v)) {
    alert("有効なURLを入力してください。");
    return;
  }
  if (customEndpoints.value.includes(v)) {
    alert("既に追加されています。");
    newEndpoint.value = "";
    return;
  }
  customEndpoints.value.push(v);
  newEndpoint.value = "";
  saveCustomEndpoints();
}

function removeEndpoint(index) {
  customEndpoints.value.splice(index, 1);
  saveCustomEndpoints();
}

function toggleSettings() {
  settingsOpen.value = !settingsOpen.value;
}

function closeSettings() {
  settingsOpen.value = false;
}

const chooseApiUrl = () => {
  // 中央管理された選択ロジックを使う（requestManager の getEffectiveApiUrl を優先）
  try {
    const u = getEffectiveApiUrl();
    if (typeof u === "string" && u) return u;
  } catch (e) {
    // ignore and fallback to local selection
  }
  // fallback: local selection mirroring previous behavior
  const customs = customEndpoints.value || [];
  if (mode.value === "existing") return apiurl();
  if (mode.value === "custom") return customs.length ? customs[Math.floor(Math.random() * customs.length)] : apiurl();
  const pool = [...customs];
  pool.push(apiurl());
  return pool.length ? pool[Math.floor(Math.random() * pool.length)] : apiurl();
};

const submitSearch = () => {
  const trimmed = query.value.trim();
  if (!trimmed) return;
  suggestions.value = [];
  selectedIndex.value = -1;
  
  // Check if it's just a video ID (11 characters, alphanumeric, dash, underscore)
  if (/^[a-zA-Z0-9_-]{11}$/.test(trimmed)) {
    router.push(`/watch?v=${trimmed}`);
    return;
  }
  
  // Check if input is a YouTube video URL
  const videoUrlMatch = trimmed.match(/(?:youtube\.com\/watch\?v=|youtu\.be\/)([a-zA-Z0-9_-]{11})(?:[&?]|$)/);
  if (videoUrlMatch && videoUrlMatch[1]) {
    router.push(`/watch?v=${videoUrlMatch[1]}`);
    return;
  }
  
  // Check if it looks like a channel ID (starts with UC and is 24 characters total)
  const channelIdMatch = trimmed.match(/^(UC[a-zA-Z0-9_-]{22})$/);
  if (channelIdMatch) {
    router.push(`/channel/${channelIdMatch[1]}`);
    return;
  }
  
  // Check if input is a YouTube channel URL
  const channelUrlMatch = trimmed.match(/youtube\.com\/(?:channel\/|c\/|@|user\/)([a-zA-Z0-9_-]+)/);
  if (channelUrlMatch && channelUrlMatch[1]) {
    router.push(`/channel/${channelUrlMatch[1]}`);
    return;
  }
  
  const chosen = chooseApiUrl();
  // 互換性維持: 既存ハンドラ向けに文字列のみを emit
  emit("search", trimmed);
  // 拡張情報が必要なコンポーネント向けに別イベントを emit
  emit("searchMeta", { query: trimmed, apiUrl: chosen, mode: mode.value });
};

const onSubmit = () => {
  submitSearch();
};

const clearQuery = () => {
  query.value = "";
  suggestions.value = [];
  selectedIndex.value = -1;
};

// mode を変更したら localStorage に保存（他コンポーネントと同期するため）
watch(mode, (v) => {
  try {
    rmSaveMode(v);
  } catch (e) {}
});
</script>

<style scoped>
.clear-button {
  position: absolute;
  right: 1.9em;
  bottom: -1px; 
  background: transparent;
  border: none;
  font-size: 1.5em;
  cursor: pointer;
  color: #555;
  padding: 0 0.5em;
  height: calc(100% - 1px);
  display: flex;
  align-items: center;
  justify-content: center;
  line-height: 1;
  user-select: none;
  transition: color 0.2s ease;
}

.clear-button:hover {
  color: #000; 
}

.header-wrapper {
  display: flex;
  align-items: center;
  justify-content: space-between;
  width: 100%;
  max-width: 100vw;
  padding: 0.5rem 1rem;
  box-sizing: border-box;
  background-color: white;
  box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
  z-index: 1000;
  height: 54px; 
  position: fixed; 
  top: 0;
  left: 0;
}

.home-button {
  border: none;
  background: transparent;
  color: #030303;
  font-size: 16px;
  padding: 8px 14px;
  border-radius: 4px;
  width: auto;
  height: 36px;
  cursor: pointer;
  user-select: none;
  font-weight: bold;
  display: flex;
  align-items: center;
  justify-content: center;
  transition: background-color 0.2s ease;
  flex-shrink: 0;
}

.home-button:hover {
  background: rgba(0, 0, 0, 0.05);
}

.logo-icon {
  height: 20px;
  width: auto;
  color: #030303;
}

.header-search {
  display: flex;
  align-items: center;
  flex: 1;
  max-width: 600px;
  margin: 0 auto;
  position: relative;
  height: 40px; 
}

.search-input {
  flex: 1;
  height: 100%;
  padding: 5px 12px 7px 12px; 
  line-height: 28px;
  border-radius: 20px 0 0 20px;
  border: 1px solid #ccc;
  outline: none;
  font-size: 1rem;
  box-sizing: border-box;
  text-align: left;
  vertical-align: middle;
  transition: border-color 0.2s;
}

.search-input:focus {
  border-color: #1c62b9;
  border-width: 1px;
}

.search-button {
  border-radius: 0 20px 20px 0;
  border: 1px solid #ccc;
  border-left: none;
  background-color: #f8f8f8;
  cursor: pointer;
  padding: 0 20px;
  font-size: 1.1rem;
  user-select: none;
  height: 100%;
  line-height: 1;
  display: flex;
  align-items: center;
  justify-content: center;
  transition: background-color 0.2s;
}

.search-button:hover {
  background-color: #f0f0f0;
}

.suggestions-list {
  position: absolute;
  top: 100%;
  left: 0;
  right: 0;
  background: white;
  border: 1px solid #ccc;
  border-top: none;
  max-height: 250px;
  overflow-y: auto;
  z-index: 10;
  border-radius: 0 0 10px 10px;
  margin: 0;
  padding: 0;
  list-style: none;
}

.suggestions-list li {
  padding: 0.5em 1em;
  cursor: pointer;
}

.suggestions-list li.selected,
.suggestions-list li:hover {
  background-color: #f0f0f0;
}

/* 設定UI用スタイル */
.header-settings {
  position: relative;
  margin-left: 0.5rem;
  flex-shrink: 0;
}

.settings-button {
  border: none;
  background: transparent;
  font-size: 1.2rem;
  cursor: pointer;
  padding: 6px;
}

.settings-modal {
  position: absolute;
  right: 0;
  top: calc(100% + 6px);
  width: 320px;
  background: #fff;
  border: 1px solid #ddd;
  box-shadow: 0 6px 20px rgba(0,0,0,0.12);
  padding: 12px;
  z-index: 2000;
  border-radius: 8px;
}

.settings-modal h3 {
  margin: 0 0 8px 0;
  font-size: 1rem;
}

.mode-group label {
  display: block;
  margin-bottom: 6px;
  font-size: 0.9rem;
}

.custom-list h4 {
  margin: 8px 0 6px 0;
  font-size: 0.95rem;
}

.custom-list ul {
  max-height: 120px;
  overflow-y: auto;
  padding: 0;
  margin: 0 0 8px 0;
  list-style: none;
}

.custom-list li {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 4px 0;
  font-size: 0.85rem;
}

.endpoint-text {
  word-break: break-all;
  margin-right: 8px;
  font-size: 0.85rem;
  color: #333;
}

.remove-btn {
  background: #f66;
  border: none;
  color: #fff;
  padding: 4px 6px;
  border-radius: 4px;
  cursor: pointer;
  font-size: 0.8rem;
}

.add-row {
  display: flex;
  gap: 6px;
}

.add-row input[type="text"] {
  flex: 1;
  padding: 6px;
  font-size: 0.9rem;
  border: 1px solid #ccc;
  border-radius: 4px;
}

.add-row button {
  padding: 6px 8px;
  cursor: pointer;
}

.settings-actions {
  text-align: right;
  margin-top: 8px;
}

.settings-actions button {
  padding: 6px 8px;
}

.playback-default {
  margin: 10px 0;
}

.playback-default h4 {
  margin: 6px 0;
  font-size: 0.95rem;
}
</style>
