<template>
  <div class="app">
    <header>
      <div class="header__content">
        <div class="header__content__search">
          <input type="text" placeholder="Search by title">
        </div>
        <div class="header__content__add">
          <button>
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" width="72" height="72"><path fill="none" d="M0 0h24v24H0z" /><path d="M11 11V5h2v6h6v2h-6v6h-2v-6H5v-2z" fill="rgba(255,255,255,1)" /></svg>
          </button>
        </div>
        <div class="header__content__filters">
          <select id="filters" name="filters">
            <option value="1">
              Filter one
            </option>
            <option value="2">
              Filter two
            </option>
            <option value="3">
              Filter three
            </option>
          </select>
        </div>
      </div>
    </header>
    <div class="selectedfilters">
      <div class="selectedfilters__filter">
        <div class="selectedfilters__filter__button">
          <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" width="24" height="24"><path fill="none" d="M0 0h24v24H0z" /><path d="M12 22C6.477 22 2 17.523 2 12S6.477 2 12 2s10 4.477 10 10-4.477 10-10 10zm0-11.414L9.172 7.757 7.757 9.172 10.586 12l-2.829 2.828 1.415 1.415L12 13.414l2.828 2.829 1.415-1.415L13.414 12l2.829-2.828-1.415-1.415L12 10.586z" fill="rgba(255,255,255,1)" /></svg>
        </div>
        <div class="selectedfilters__filter__text">
          Filter one
        </div>
      </div>
      <div class="selectedfilters__filter">
        <div class="selectedfilters__filter__button">
          <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" width="24" height="24"><path fill="none" d="M0 0h24v24H0z" /><path d="M12 22C6.477 22 2 17.523 2 12S6.477 2 12 2s10 4.477 10 10-4.477 10-10 10zm0-11.414L9.172 7.757 7.757 9.172 10.586 12l-2.829 2.828 1.415 1.415L12 13.414l2.828 2.829 1.415-1.415L13.414 12l2.829-2.828-1.415-1.415L12 10.586z" fill="rgba(255,255,255,1)" /></svg>
        </div>
        <div class="selectedfilters__filter__text">
          Filter one
        </div>
      </div>
      <div class="selectedfilters__filter">
        <div class="selectedfilters__filter__button">
          <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" width="24" height="24"><path fill="none" d="M0 0h24v24H0z" /><path d="M12 22C6.477 22 2 17.523 2 12S6.477 2 12 2s10 4.477 10 10-4.477 10-10 10zm0-11.414L9.172 7.757 7.757 9.172 10.586 12l-2.829 2.828 1.415 1.415L12 13.414l2.828 2.829 1.415-1.415L13.414 12l2.829-2.828-1.415-1.415L12 10.586z" fill="rgba(255,255,255,1)" /></svg>
        </div>
        <div class="selectedfilters__filter__text">
          Filter one
        </div>
      </div>
    </div>
    <div class="counters">
      <div class="counters__counter">
        <div class="counters__counter__text">
          Items
        </div>
        <div class="counters__counter__controls">
          <div class="add">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" width="36" height="36"><path fill="none" d="M0 0h24v24H0z" /><path d="M12 22C6.477 22 2 17.523 2 12S6.477 2 12 2s10 4.477 10 10-4.477 10-10 10zm-1-11H7v2h4v4h2v-4h4v-2h-4V7h-2v4z" fill="rgba(255,255,255,1)" /></svg>
          </div>
          <div class="number">
            20
          </div>
          <div class="rest">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" width="36" height="36"><path fill="none" d="M0 0h24v24H0z" /><path d="M12 22C6.477 22 2 17.523 2 12S6.477 2 12 2s10 4.477 10 10-4.477 10-10 10zM7 11v2h10v-2H7z" fill="rgba(255,255,255,1)" /></svg>
          </div>
          <div class="del">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" width="36" height="36"><path fill="none" d="M0 0h24v24H0z" /><path d="M12 22C6.477 22 2 17.523 2 12S6.477 2 12 2s10 4.477 10 10-4.477 10-10 10zm0-2a8 8 0 1 0 0-16 8 8 0 0 0 0 16zm0-9.414l2.828-2.829 1.415 1.415L13.414 12l2.829 2.828-1.415 1.415L12 13.414l-2.828 2.829-1.415-1.415L10.586 12 7.757 9.172l1.415-1.415L12 10.586z" fill="rgba(162,164,203,1)" /></svg>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'IndexPage'
}
</script>
<style lang="scss">
@import url('https://cdnjs.cloudflare.com/ajax/libs/normalize/8.0.1/normalize.min.css');
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@300;500&display=swap');

  body{
    background-color: #CFD2E5;
    color: #425489;
    font-family: 'Roboto', sans-serif;
    font-weight: 300;
  }
  .app{
    background: #EFF3FD;
    box-shadow: 0px 14px 25px 5px rgba(162, 164, 203, 0.6);
    border-radius: 80px;
    max-width: 800px;
    margin: 30px auto;
    min-height: 60vh;
  }
  header{
      background: #FFFFFF;
      border-radius: 50px 50px 0px 0px;
      .header__content{
        padding: 30px;
        position: relative;
        &__add{
          position: absolute;
          right: 30px;
          top: 30px;
          button{
            background-color: #536CE3;
            height: 110px;
            width: 110px;
            border-radius: 50%;
            border: 0;
            cursor: pointer;
            box-shadow: 0px 14px 25px 5px rgba(162, 164, 203, 0.6);
            transition: background-color 0.3s ease;
            &:hover{
              background-color: #425489;
            }
          }
        }
        &__search{
          width: calc(100% - 140px);
          input{
            width: calc(100% - 70px);
            height: 30px;
            padding: 15px 15px 15px 60px;
            background: #E0E3F4;
            border-radius: 60px;
            border: 0;
            color: #425489;
            background-image: url( 'data:image/svg+xml,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" width="36" height="36"><path fill="none" d="M0 0h24v24H0z"/><path d="M18.031 16.617l4.283 4.282-1.415 1.415-4.282-4.283A8.96 8.96 0 0 1 11 20c-4.968 0-9-4.032-9-9s4.032-9 9-9 9 4.032 9 9a8.96 8.96 0 0 1-1.969 5.617zm-2.006-.742A6.977 6.977 0 0 0 18 11c0-3.868-3.133-7-7-7-3.868 0-7 3.132-7 7 0 3.867 3.132 7 7 7a6.977 6.977 0 0 0 4.875-1.975l.15-.15z" fill="rgba(162,164,203,1)"/></svg>' );
            background-repeat: no-repeat;
            background-position: 10px center;
            outline: none;
            box-shadow: 0px 1px 1px 5px rgba(162, 164, 203, 0);
            transition: box-shadow 0.3s ease;
            &::-moz-placeholder{
              color: #A2A4CB;
            }
            &:focus,
            &:active,
            &:hover{
              box-shadow: 0px 14px 25px 5px rgba(162, 164, 203, 0.6);
            }
          }
        }
      }
  }
  .selectedfilters{
    display: flex;
    width: 100%;
    margin: 30px;
    .selectedfilters__filter{
      align-items: center;
      display: flex;
      width: 120px;
      height: 22px;
      background: #D76CA6;
      border-radius: 15px;
      margin-right: 15px;
      color: #FFFFFF;
      padding: 4px;
      font-size: 14px;
      box-shadow: 0px 14px 25px 5px rgba(162, 164, 203, 0.6);
      svg{
        display: block;
        margin-right: 4px;
        cursor: pointer;
      }
      &:nth-child(odd){
        background: #A2A4CB;
      }
    }
  }
  .counters{
    margin: 30px;
    &__counter{
      display: flex;
      justify-content: space-between;
      background: #425489;
      border-radius: 60px;
      color: #FFFFFF;
      padding: 30px;
      &__controls{
        display: flex;
      }
    }
  }
</style>
